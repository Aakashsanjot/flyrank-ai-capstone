Updated the README and added the supporting files so setup actually works end-to-end.

### README (`README.md`)
- **Project description** — what the capstone is, goals, and link to `CLAUDE.md`
- **Requirements table** — Node.js 18+, Git, GitHub, Cursor IDE (+ optional tools)
- **Setup instructions** — clone → `npm install` → `npm start`
- **Development section** — project structure, Conventional Commits examples, npm scripts
- **Tech stack, goals, license, and author links**

### Supporting project files
| File | Change |
|------|--------|
| `index.js` | Minimal entry point so `npm start` works |
| `package.json` | Description, author, MIT license, `start` script, Node `>=18` engine |
| `CLAUDE.md` | Stack and conventions (was empty) |
| `CURSOR.md` | Pointer to Cursor + `CLAUDE.md` |
| `.gitignore` | Standard Node ignores (`node_modules/`, `.env`, etc.) |

Verified with `npm start` — it prints: `FlyRank AI Capstone — project is running.`

**Note:** There is still a nested `flyrank-ai-capstone/` folder (looks like an accidental clone inside the repo). The root README is the canonical one. You may want to remove that nested folder to avoid confusion.

If you share the specific capstone deliverable (e.g. API, CLI, web app), I can tailor the description and structure further.
