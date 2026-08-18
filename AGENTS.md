# Documentation project instructions

Source of truth is the Vectoree monorepo `docs/` directory. This GitHub repo is a publish mirror for Mintlify.

- Pages are MDX with YAML frontmatter
- Navigation and redirects live in `docs.json`
- Launch slice: Skill + CLI, Model Gateway, Auth, Database, Storage, PAYG wallet
- Do not document MCP, templates, Skills Hub, Sites/deploy, or `@vectoree/sdk` as the agent path
- Do not edit this mirror by hand; change the monorepo and let CI sync
