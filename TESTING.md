# TESTING — @restart/papercup-db

## What this project's tests cover

- (none yet) — drop `*.test.ts` files alongside source and they'll be
  picked up by `npm test`.

## What they don't cover

- Drizzle schema for the papercup app DB.
- Browser flows — verified ad-hoc via the `verdict` skill.

## Run after editing

| Edit touches                        | Run                                                   |
| ----------------------------------- | ----------------------------------------------------- |
| Anything in this workspace          | `npm test --workspace @restart/papercup-db`                       |
| Code that other workspaces depend on| `npm run test:affected` from repo root               |

See repo-root `CLAUDE.md` for the full testing strategy.
