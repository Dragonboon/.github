# Agent guide — Dragonboon organization profile

Scope: the Dragonboon **organization presentation repository** only. It is not a Godot runtime addon. The public organization landing page is `profile/README.md`.

## Purpose and ownership

- Maintain a clear, accessible and professional discovery page for the existing Dragonboon projects. The landing page is **bilingual: English and Spanish**.
- The canonical project facts (functionality, installation, supported Godot versions and maturity) live in each project's own README and documentation. Check the relevant repository before updating its description.
- Do not claim a repository exists, is actively supported or has a verified feature without checking. Keep repository links, icons and sections aligned with the current organization inventory.
- Preserve explicit separation between English and Spanish sections, including working anchors and navigation. Keep equivalent project information in both languages; avoid accidental untranslated additions.
- Use descriptive link text, meaningful image alt text, readable Markdown/HTML and reasonably sized icons. Prefer light styling and simple tables over fragile decoration.
- Limit edits to `profile/README.md` and closely related profile assets unless the task explicitly extends scope. Never modify other repositories from this profile repository by implication.

## Low-cost working process

1. Read `profile/README.md`, then check only the repos whose entries are affected. Use narrow lookups to avoid repeatedly pulling entire unrelated project trees.
2. For repo additions/renames, validate the repository URL, icon asset path, public visibility and its actual stated purpose.
3. Make the smallest bilingual update, preserving headings, anchor links and separation; avoid rewriting otherwise correct prose or regenerating unrelated assets.
4. Manually review rendered Markdown, internal anchors, accessibility text and links in both languages. There is no Godot build or runtime test suite in this profile repository.
5. Commit to current `main` only when explicitly authorized, without overwriting concurrent edits. Report changed sections and what link/render checks were performed.

## Safety and truthfulness

Never publish private repository information, secrets, unpublished roadmaps or unverified status claims. Treat icons and images as credited assets. Keep `AGENTS.md` as contributor guidance—not part of the public README copy.

## Evidence contract for profile changes

Before editing, list the entries/languages affected, their canonical public source
and the visible navigation outcome. For an organization inventory refresh, enumerate
all accessible pages and distinguish public repositories from inaccessible/private
ones; never infer their names from earlier conversation. Check each affected default
branch rather than copying descriptions or maturity claims from an unmerged PR.
Do not impose a shared engine version, addon namespace or release status across
independent projects.

Keep one canonical entry per repository and equivalent facts in English/Spanish.
Validate local asset paths and heading anchors separately from external URLs.
Use the smallest relevant source excerpt instead of reading every repository.
For documentation-only changes, link/path review is sufficient; only report a
rendered review if the rendered page was actually observed. No engine build,
runtime suite or invented CI is needed.

Record the source repositories/branches checked, changed entries, link/anchor
results and any inaccessible sources. Do not claim a project is production-ready
or that agents are more effective without evidence. Publishing authorization is
task-specific; protect concurrent changes by checking the branch head before
updating it and never force-push.
