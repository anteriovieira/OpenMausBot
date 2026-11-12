# Radar Scout connection

Radar Scout's hosted MCP server is `https://mcp.radarscout.com.br/mcp`. It
uses streamable HTTP and OAuth with a Radar Scout account; no API key is
needed. Radar Scout supports Amazon, Mercado Livre and other marketplaces;
its feature list includes seller sales, profit, settlements, catalog,
inventory, repricing and Ads. Ads actions require reviewing a simulation and
confirming the change.

## Live acceptance (account owner required)

In Plugins, connect Radar Scout and complete its OAuth sign-in. Confirm that
the tool list loads, then use a bot with Radar Scout selected under Bot access
to make a read-only query about a connected seller account. Do not approve
an Ads change as a connection smoke test. Disconnect and confirm the server is
no longer available to a bot's next task.
