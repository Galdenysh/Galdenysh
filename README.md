**👋 Hi, I'm Igor Petrov**
- 💼 Frontend Developer with commercial development experience
- 🛠️ **Core Stack:** React, TypeScript, Next.js, Node.js (Express/Nest.js)
- 🎯 **Focus Areas:** High-load interfaces, Component Architecture, Performance, a11y
- ⚙️ **Also interested in:** Internal tools, CI/CD, and developer experience
- 📱 **Contact me on:** My Telegram [@Galdenysh](https://t.me/galdenysh)

## How I work with coding agents

I treat the agent as an implementer, not as the author of the plan.

On [kuren-01](https://github.com/Galdenysh/kuren-01) I did not write the app by hand. I wrote the operating contract, and agents implemented a small XOR lab (TypeScript MLP, React view, GitHub Pages) inside it:

- Spec before code. A slice starts as an OpenSpec change (`proposal`, delta spec, `design`, `tasks`). Implementation starts only after I review the plan.
- Area law, not a giant prompt. Root `AGENTS.md` is an index. Rules live next to the code: core, UI, and the slice workflow. Cursor rules are an adapter, not the source of truth.
- Hard gates. Core is TDD. UI starts only after core tests are green. `npm run verify` (agent index, lint, format, test, build) is the only definition of done. `agents:check` fails if the agent index drifts.
- Scope stays small. One change per session. Bugfixes of already-specified behavior do not get a new change.

The network is a teaching toy. The workflow is the thing I would reuse on a product codebase.

<!---
Galdenysh/Galdenysh is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
