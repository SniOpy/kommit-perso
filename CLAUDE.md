# kommit-perso

## Résumé

Ce repo n'est pas un projet applicatif. Il héberge **ma configuration Claude Code personnelle** (règles de comportement et skills) et englobe les 2 repos de l'équipe Kommit : `kommit-backend/` et `kommit-frontend/`. Ces 2 repos sont indépendants, avec des stacks différentes, et sont ignorés par git ici.

Ma config n'a pas sa place dans les repos de l'équipe, et pas dans `~/.claude` non plus, car elle s'appliquerait alors à tout le reste de la machine. Elle vit donc ici, à l'échelle du projet.

Ce repo ne contient que ce qui resterait vrai si je changeais de projet : façon de répondre, raccourcis, conventions d'écriture. Rien sur la structure ou les conventions du code de l'équipe, qui appartiennent à leurs repos.

## Arborescence

```
kommit-perso/
├── CLAUDE.md
├── .gitignore
├── .claude/
│   ├── CLAUDE.md                  # instructions du projet
│   ├── settings.json
│   ├── rules/                     # règles de comportement
│   │   ├── chiffres-en-chiffres.md
│   │   ├── concision-brainstorming.md
│   │   ├── concision.md
│   │   ├── ecriture-skills-et-agents.md
│   │   ├── git.md
│   │   ├── no-echo.md
│   │   ├── own-errors-immediately.md
│   │   ├── parle-clair.md
│   │   ├── pas-de-nuance-gratuite.md
│   │   ├── pas-de-style.md
│   │   ├── pas-de-tiret-cadratin.md
│   │   └── raccourcis.md
│   └── skills/
│       ├── delete-sessions/       # SKILL.md + scripts/ (delete_sessions.sh, list_sessions.py)
│       ├── handoff/
│       ├── recap/
│       ├── recover-sessions/
│       └── start-ticket/
├── .vscode/
│   └── settings.json
├── kommit-backend/                # repo de l'équipe, ignoré par git
└── kommit-frontend/               # repo de l'équipe, ignoré par git
```
