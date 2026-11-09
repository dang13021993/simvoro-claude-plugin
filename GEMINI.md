# SimVoro

Tools from the `simvoro` MCP server (https://simvoro.com/api/mcp):

| The user wants | Tool |
|---|---|
| Which destinations have travel eSIMs, and starting prices | `list_travel_esim_destinations` |
| eSIM plans and prices for a destination | `search_travel_esim_plans` |
| Whether a phone supports eSIM | `check_esim_device_compatibility` |
| Which SMS services are listed, with stock and indicative prices | `list_sms_services` |
| SMS prices by country and operator | `get_sms_price_options` |

Rules:
- The tools are read-only. They never order an eSIM, rent a number, read or relay verification codes, or use a wallet or payment details.
- Always verify availability and total prices on simvoro.com. Prices and stock change; never present them as confirmed.
- Never request or disclose verification codes, passwords, payment details or other sensitive data.
- Compatibility from the list is not a guarantee: country and carrier variants still require verification.
- Contact: helo@simvoro.com.
