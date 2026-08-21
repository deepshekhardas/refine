# Contributing to Refine

Thanks for your interest in contributing! This is a quick start for first-time contributors. For the full guide, see [Contributing](https://refine.dev/docs/contributing/).

## Quick Start for Beginners

1. **Fork & clone** — fork `refinedev/refine` on GitHub, then `git clone https://github.com/<your-username>/refine.git` and `git remote add upstream https://github.com/refinedev/refine.git`.
2. **Install dependencies** — `pnpm install` (uses workspaces; `--ignore-scripts` skips builds if you want it faster).
3. **Run packages/examples** — `pnpm dev --scope <package> --scope <example>` (watch mode, e.g. `--scope @refinedev/antd --scope base-antd`).
4. **Run tests** — `pnpm test -- --scope <package>` (Jest + Testing Library).
5. **Lint & format** — use the [Biome VSCode extension](https://biomejs.dev/reference/vscode/) or run biome; markdown is formatted with Prettier.
6. **Create a changeset** — `pnpm changeset` (select package, bump type, write summary linked to an issue).
7. **Commit & push** — conventional commits (`feat(core): ...` / `fix(antd): ...`), then `git push origin <branch>` and open a PR against `main`.

Refer to our full contribution guide here: [Contributing](https://refine.dev/docs/contributing/)
