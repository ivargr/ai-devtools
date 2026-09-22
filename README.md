# ai-devtools

AI development tools for the DHIS2 ecosystem — published as standalone npm packages from this monorepo.

For guidance on using AI agents to build DHIS2 applications, see the [AI-assisted App Development guide](https://developers.dhis2.org/docs/guides/ai-development) on the DHIS2 Developer Portal.

## Install skills

> **Attribution** — `@dhis2/skill-dhis2-apps` is based on [dhis2-app-skills](https://github.com/devotta-labs/dhis2-app-skills) by [Eirik Haugstulen](https://github.com/eirikur-haugstulen) at [Devotta Labs](https://github.com/devotta-labs).

Available skills:

- `dhis2-apps` — build custom DHIS2 web applications with the DHIS2 App Platform
- `discourse` — search, read and draft posts on the [DHIS2 Community of Practice](https://community.dhis2.org) via the Discourse MCP server

```sh
# All skills (interactive prompt to select)
npx skills add dhis2/ai-devtools

# A specific skill by name
npx skills add dhis2/ai-devtools --skill dhis2-apps
npx skills add dhis2/ai-devtools --skill discourse

# A specific skill by path
npx skills add https://github.com/dhis2/ai-devtools/tree/main/src/skills/dhis2-apps
```

## Contributing

```sh
pnpm install        # install dependencies
pnpm lint           # check formatting
pnpm changeset      # record a changeset before opening a PR
```

See [CLAUDE.md](./CLAUDE.md) for repo structure and release flow details.
