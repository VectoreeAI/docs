# Documentation project instructions

Source of truth is the Vectoree monorepo `docs/` directory. This GitHub repo is a publish mirror for Mintlify.

- Pages are MDX with YAML frontmatter
- Navigation and redirects live in `docs.json`
- Launch slice: Skill + CLI, Templates, Model Gateway, Tool Hub, Auth, Database, Storage, PAYG wallet
- Agent path is Skill + CLI (optional start from Dashboard Templates). Tool Hub is hosted MCP, not Skills Hub
- Do not document `@vectoree/sdk` as the agent path. Deploy / Payments are coming soon
- This GitHub repo is what Mintlify publishes; edit pages here when that is the requested workflow
