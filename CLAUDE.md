# CLAUDE.md

@AGENTS.md
@.claude/CLAUDE.md
@.claude/MODEL-LINK.md

<!-- MODEL-BODY: MasterModel.bd — dieses Repo ist ein Body des Models. Die @.claude/MODEL-LINK.md
     oben lädt Regeln/Skills/Guards + Lern-Schleife des Models (Muster ins Model, Fall bleibt hier). -->

This project uses [AGENTS.md](https://agents.md/) as the standard for providing context to AI coding agents. The `@AGENTS.md` import above tells Claude Code to load `AGENTS.md` automatically; other tools that natively support `AGENTS.md` will pick it up directly. The `@.claude/CLAUDE.md` import loads the local hard-rules file (gitignored) that mirrors the PostToolUse hook policy.
