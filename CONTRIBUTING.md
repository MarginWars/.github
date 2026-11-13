# Contributing

These rules apply to people and to automated agents in every MarginWars repository. A repository's own
`CONTRIBUTING.md` adds to them; [themarginwars](https://github.com/MarginWars/themarginwars/blob/main/CONTRIBUTING.md)
has the full version.

## Branches and commits

- Branch from `main` with a short-lived branch: `feat/`, `fix/`, `docs/`, `chore/` or `ci/`.
- Commits follow [Conventional Commits](https://www.conventionalcommits.org/): `<type>(<scope>): <summary>`,
  imperative, at most 72 characters.

## Pull requests

1. Everything lands through a pull request that uses the template and links its issue.
2. Every required check must pass.
3. The code owner approves. **The merge is the approval of record** for exactly what is in the pull request.
4. **Squash-merge only.** The pull request title becomes the commit, so it must be a Conventional Commit.
5. Agents open pull requests and never approve, merge or bypass a ruleset. Agents prepare. People sign.

## Style

- One H1 per file, sentence-case headings, and "The Margin Wars" in full when naming the brand.
- Plain and precise. Never invent facts: every number cites a source or is marked as an assumption.
- No secrets or personal data, ever. See [SECURITY.md](SECURITY.md).
