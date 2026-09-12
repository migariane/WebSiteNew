# CLAUDE.md

This file provides guidance to Claude Code when working with code in this repository.

**Project:** maluque.netlify.app — MALF personal site (Hugo-Apero)
**Author:** Miguel Angel Luque-Fernandez
**Deploy:** Netlify (`netlify.toml`); baseURL https://maluque.netlify.app/
**Stack:** Hugo + `hugo-apero` theme (Academic-like)

---

## Project Structure

```
mluque_apero/
├── config.toml           # Site config: title "MALF", menus, params, author
├── content/              # _index.md + sections: home, project, publication, talk
├── layouts/              # Template overrides (va acima del theme)
├── static/ data/         # Static assets, site data files
├── themes/hugo-apero/    # Theme (vendored; also themes via gitmodules)
├── resources/ public/    # Build artifacts (cached / rendered) — git-ignored or regenerable
├── netlify.toml          # Netlify build config
└── mluque_apero.Rproj .Rhistory  # RStudio residue — ignore
```

## Key Commands

```bash
# Serve locally with drafts
hugo server -D

# Build site into public/
hugo

# Deploy (production branch is master; do NOT touch origin/main — it is abandoned junk)
git push origin master   # Netlify auto-builds from repo
```

## Main Content Sections (content/)

- `home` — landing / about
- `project` — portfolio items
- `publication` — publications listing
- `talk` — presentations/workshops
- Menus driven from `config.toml` (About, Publications, Project Portfolio, Talks, Teaching, Contact, Statistical Tutorials)

## Development Notes

- Author shortname: **MALF**; RSS/DOI metadata live in `config.toml`
- The theme ships a large sketchy config surface — prefer **minimal overrides in `config.toml`/`layouts/`** over editing `themes/hugo-apero/` directly
- `themes/hugo-apero/` is a **git submodule** (upstream `hugo-apero/hugo-apero.git`): NEVER edit its files — edits vanish on Netlify (clones by recorded hash). Shadow theme partials with same-named files under site `layouts/` (e.g. `layouts/partials/footer.html`)
- `.quarto/`, `.hugo_build.lock`, `public/` are generated — do not commit
- `hugo-apero-main.zip` is the upstream theme archive reference