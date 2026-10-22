# Metix AI Platform for Perplexity

The plugin Perplexity imports. It searches people, companies, and job postings on the [Metix AI Platform](https://platform.metix.ai), then you sign in with your own account.

Inside Perplexity the plugin and the connector are named `metix-ai-platform`. That is this platform. Metix at metix.ai is a different product.

The repository root holds `plugin.json` and `mcp.json`. There is no API key in the package, and there are no skills.

## Import

In Perplexity Computer, open Plugins, choose Add custom, then Import plugin from GitHub, and paste:

https://github.com/MetixAI-Official/metix-ai-platform-perplexity

Open the plugin and choose Connect. Leave contact unlock unticked.

On a question, open the plus menu, then Connectors, and check `metix-ai-platform`.

## Updates

Perplexity copies the repository when you import it. A later push does not change a plugin you already imported. Open the plugin, choose More actions, then Replace file, and upload a zip of `plugin.json` and `mcp.json` from this root. Or delete the plugin and import the URL again.

The zip has those two files at its root, not inside a folder. The server type is `streamable-http` and the URL is `https://mira-api.metix.ai/mcp`, with no headers.
