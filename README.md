# Stackfolio

A Powerhouse application scaffolded with `ph init --uniform-runners`: one
package, several uniform hosts that all run the same stack.

## Layout

| Path | What |
|---|---|
| `document-models/` | Document models (specs + generated code + reducers) |
| `editors/` | Editors for the document models |
| `processors/` | Relational processors |
| `subgraphs/` | Subgraphs |
| `hosts/` | Uniform runners: `connect`, `switchboard`, `cli`, `desktop`, `assistant`, `vetra` |
| `reactor/` | Reactor setup |

## Commands

```bash
pnpm install
pnpm vetra        # switchboard + Connect dev environment
pnpm connect      # Connect in studio mode
pnpm build        # build the library for the registry
pnpm tsc          # type-check package and hosts
pnpm test         # vitest
```
