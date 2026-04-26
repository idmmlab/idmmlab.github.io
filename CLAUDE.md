# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

@AGENTS.md

## Repo-Specific Context

This is the **IDMM Lab fork** of the upstream [al-folio](https://github.com/alshedivat/al-folio) Jekyll academic theme (Soongsil University, IDMM Lab). Most conventions, commands, and file layout come from upstream al-folio (covered via the `@AGENTS.md` import above and the files it links to). This section captures what is specific to this fork.

### Deployment target

Served as a **project site**, not a personal site. In `_config.yml`:

- `url: https://kanghyunl.github.io`
- `baseurl: "/idmmlab.github.io"`

The pair must stay in sync — changing one without the other breaks CSS/JS asset URLs on the deployed site. Always use `{{ '/path' | relative_url }}` in templates instead of hard-coding `/`-prefixed paths, otherwise links break under the baseurl.

### Custom additions beyond stock al-folio

- `_data/members.yml` — lab member roster (not present upstream).
- `_pages/people.md` — renders the members page from `members.yml`.
- `_pages/research.md` — lab research overview page.
- `_sass/_themes.scss` — customized theme colors for IDMM Lab branding.

When touching members/research/theme: check whether the upstream pattern (e.g., `_data/socials.yml`, `_data/coauthors.yml`) applies before inventing a new structure.

### Environment notes

- Development host is **Windows**; the AGENTS.md commands assume a Unix shell. Run Docker commands from Git Bash, WSL, or PowerShell — `docker compose` itself is cross-platform.
- Prettier is configured with `printWidth: 150` and the `@shopify/prettier-plugin-liquid` plugin (`.prettierrc`). Run `npx prettier . --write` before committing; the `prettier.yml` CI workflow fails PRs on unformatted code.

### Commit convention

This fork follows the upstream `<type>: <subject>` convention documented in `.github/GIT_WORKFLOW.md` (`feat`, `fix`, `docs`, `style`, `config`, `chore`). Stage files explicitly — avoid `git add .`.

### Before recommending an upstream solution

The AGENTS.md / copilot-instructions.md references cover stock al-folio. Before suggesting a change based on them, check whether this fork has already diverged (members, research page, theme, `_config.yml` values). If the fork has overridden the upstream pattern, match the fork's pattern rather than reverting to upstream.
