# Contributing to Awesome MCP Servers

Thank you for your interest in contributing! This list aims to be the most comprehensive and well-organized collection of MCP servers.

## How to Add a New Server

1. Fork this repository
2. Add your server to the appropriate category in `README.md`
3. Submit a Pull Request

### Entry Format

Each entry should follow this format:

```markdown
| [Name](https://github.com/owner/repo) | One-line description (max 80 chars) | `install command` | [![GitHub](https://img.shields.io/github/stars/owner/repo?style=flat-square)](https://github.com/owner/repo) |
```

### Requirements

- **Working repository**: The GitHub repo must be public and accessible
- **MCP compatible**: The server must implement the [Model Context Protocol](https://modelcontextprotocol.io/)
- **Description**: Keep it to one clear sentence (max 80 characters)
- **Install command**: Provide the simplest install command (npx, pip, uvx, etc.)
- **Correct category**: Place in the most relevant category
- **Alphabetical order**: Add entries in alphabetical order within each category

### Quality Guidelines

- The server should have a README with setup instructions
- It should be actively maintained (commits within the last 6 months)
- Prefer official/first-party integrations when available
- Community servers are welcome if they are well-documented

## How to Suggest a New Category

If you think a new category is needed:

1. Open an Issue with the title `[Category] Suggested category name`
2. List at least 3 servers that would fit the category
3. Explain why existing categories don't cover it

## How to Report Issues

- **Broken link**: Open an Issue with the title `[Broken] Server Name`
- **Outdated info**: Open an Issue or submit a PR with the correction
- **Duplicate entry**: Open an Issue with the title `[Duplicate] Server Name`

## Code of Conduct

- Be respectful and constructive
- No self-promotion spam — your server must be genuinely useful
- Don't remove other entries without good reason

## Questions?

Open an Issue with the `question` label. We're happy to help!
