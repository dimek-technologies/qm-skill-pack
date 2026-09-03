# qm-skill-pack

Text-only export of `~/.claude/skills` for import into QM as a skill pack.
64 skills; gstack-dependent skills and binaries excluded (they cannot run in a QM sandbox).

Layout: `skills/<id>/SKILL.md` plus text assets (scripts, references).

Regenerate from the local machine with the rsync filter used in the QM deployment session
(text extensions only, excluding node_modules/.git/__pycache__).
