# skillshelf

Reusable agent skills: review, commit, refactor, test

Side project, maintained when I have time.

## Highlights

- Each skill is a folder with a single SKILL.md
- YAML frontmatter: name + when-to-use description
- Drop-in compatible with ~/.claude/skills
- Versioned like code: review changes in PRs
- Concrete instructions, output formats and examples

## Install

```bash
git clone <this repo>
cp -r skills/* ~/.claude/skills/
```

## Usage

```bash
# skills trigger automatically on matching tasks
# or invoke directly: /code-review
```

## Project structure

```text
├── docs/
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── skills/
│   ├── code-review/
│   │   └── SKILL.md
│   ├── commit-message/
│   │   └── SKILL.md
│   ├── refactor-plan/
│   │   └── SKILL.md
│   └── test-writer/
│       └── SKILL.md
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
└── SECURITY.md
```

## License

MIT licensed, see LICENSE.
