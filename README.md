# SimVoro – eSIM & SMS Services (Claude plugin)

SimVoro offers two product categories: travel eSIM data plans for trips and public information about SMS verification number services. This Claude plugin provides **read-only guidance** for both areas, including eSIM destinations, data allowances, validity, compatible phones, and publicly advertised SMS service prices and countries. It is designed for public Claude Directory review as a skills-based plugin.

## What this plugin does

- Guides travelers to compare verified eSIM packages for their destination and trip length.
- Helps check phone eSIM support, carrier-lock status, device variant and other restrictions.
- Explains publicly listed SMS service names, countries, stock indicators and price options.
- Refers users to the official SimVoro website to verify current offers.

## Safety and limitations

The plugin has **no MCP server connection** and cannot claim live inventory without checking current public information. It cannot order eSIMs, rent temporary numbers, read or forward verification codes, spend wallet funds, use payment credentials, or register third-party accounts. It must not present uncertain availability or prices as confirmed.

## Skills included

- `start-here` — identify eSIM vs SMS needs
- `travel-esim-selector` — compare public travel eSIM plans
- `esim-phone-check` — check phone variants and eSIM compatibility
- `simvoro-sms-prices` — public SMS catalog and price research

## Official links

- Website: https://simvoro.com
- Travel eSIM: https://simvoro.com/esim
- SMS catalog: https://simvoro.com/sms
- Help: https://simvoro.com/help
- Privacy: https://simvoro.com/privacy
- Terms: https://simvoro.com/terms

## Installation and release

In Claude, open the plugin directory submission and point it to this repository's root on the `main` branch. The manifest is at `.claude-plugin/plugin.json`. This repository contains source files, not the downloadable ZIP artifact. The publisher must verify current site policies before asserting compliance and complete Anthropic's final directory review. The MIT license applies to **this plugin's files only**, not the SimVoro website, logos as trademarks, backend software or business services.
