# Devart MCP Server for PostgreSQL

Self-hosted MCP server for secure AI access to PostgreSQL.

Devart MCP Server for PostgreSQL helps connect AI tools to PostgreSQL through a production-ready MCP layer built on top of the corresponding Devart ODBC Driver.

It is designed for teams that need a faster, simpler, and more practical way to bring AI into real PostgreSQL workflows without building and maintaining a custom MCP integration from scratch.

## Why this server

Use this server when PostgreSQL is your primary source and you want a focused MCP setup optimized for that database.

Compared to a broader multi-source approach, Devart MCP Server for PostgreSQL gives you a simpler path to setup, source-specific behavior, and trusted Devart connectivity underneath.

## Key benefits

- Focused MCP server for PostgreSQL
- Self-hosted and on-premises by design
- Keeps data inside your infrastructure
- Built on the Devart ODBC Driver for PostgreSQL
- Fast setup and practical AI integration
- Designed for real workflows, not only experiments

## How it works

Devart MCP Server for PostgreSQL sits between your AI tool and your PostgreSQL database.

1. An AI tool sends a natural-language request to the MCP server.
2. The MCP server interprets the request and generates SQL.
3. The Devart ODBC Driver for PostgreSQL executes the query against PostgreSQL.
4. The MCP server transforms the result into output suitable for AI processing.
5. The AI tool receives structured data for analysis, explanation, or follow-up actions.

## Best fit

Devart MCP Server for PostgreSQL is a good fit for teams that want:

- AI-assisted access to PostgreSQL without building a custom MCP server
- SQL-free data access for analysts and business users
- Faster troubleshooting and investigation for developers and DBAs
- On-premises AI adoption where sensitive data should stay inside company infrastructure

## Typical use cases

- Explore PostgreSQL data in natural language
- Investigate production issues and query behavior
- Analyze schemas, tables, and relationships with AI assistance
- Support internal reporting and ad-hoc analysis
- Build internal AI copilots connected to PostgreSQL

## Prerequisites

- Windows environment
- PostgreSQL database
- Devart ODBC Driver for PostgreSQL
- Activated driver license where required
- A supported AI tool

## Quick start

1. Install Devart MCP Server for PostgreSQL
2. Install and activate Devart ODBC Driver for PostgreSQL
3. Configure the PostgreSQL connection
4. Connect your AI tool
5. Run your first query

## AI tool integration

Devart MCP Server for PostgreSQL is designed to work with popular AI tools, including:

- Claude Desktop
- GitHub Copilot
- JetBrains IDEs
- Other AI IDEs

## Example questions

Once connected, you can ask your AI tool questions such as:

- Show total orders by month for the last 12 months
- Which customers stopped buying recently?
- Find slow or suspicious queries in this dataset
- Explain the structure of the billing-related tables
- Show users with active subscriptions but missing last payment dates

## Documentation

- [Overview](./docs/overview.md)
- [Requirements and compatibility](./docs/requirements-and-compatibility.md)
- [Installation](./docs/installation.md)
- [Licensing](./docs/licensing-and-activation/licensing.md)
- [Activate Devart MCP Server](./docs/licensing-and-activation/activate-devart-mcp-server.md)
- [Connection configuration](./docs/connection-configuration.md)
- [AI integration](./docs/ai-integration/README.md)
- [Integrate with Claude Desktop](./docs/ai-integration/integrate-with-claude-desktop.md)
- [Integrate with GitHub Copilot](./docs/ai-integration/integrate-with-github-copilot.md)
- [Integrate with JetBrains IDE](./docs/ai-integration/integrate-with-jetbrains-ide.md)
- [Support](./docs/support.md)
- [Release notes](./docs/release-notes.md)

## Related products

- [Devart MCP Server Universal](https://github.com/devart-ai-connectivity/mcp-server-universal)
- [Devart ODBC Driver for PostgreSQL](https://www.devart.com/odbc/postgresql/)
- [Devart MCP Servers](https://www.devart.com/mcp/)

## Support

You can find answers to your questions and share feedback or suggestions about the product.

- [Documentation](https://docs.devart.com/)
- [Submit a Request](https://www.devart.com/company/contactform.html)
- [Suggest a Feature](https://devart.uservoice.com/)
- [Join Our Forum](https://support.devart.com/portal/en/community)
- [Trust Center](https://www.devart.com/data-connectivity/trust-center.html)

## Release status

This repository is being prepared as the product shell for Devart MCP Server for PostgreSQL. Code and installation artifacts may be added separately.
