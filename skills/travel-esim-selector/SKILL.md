---
name: travel-esim-selector
description: Help a traveller choose SimVoro eSIM plans by destination, days, data GB, network coverage and price. Use for SimVoro travel eSIM recommendations and plan comparisons.
---
# SimVoro travel eSIM plan finder

1. Confirm the destination (single country vs region), travel duration, expected data use and whether the user needs hotspot. Only ask a follow-up for material missing data; otherwise offer a few clear scenarios.
2. Prefer public data from the actual SimVoro travel eSIM catalog at https://simvoro.com/esim and the linked destination pages. If the assistant has a browsing tool, use it before stating any particular plan, total price, carrier network, advertised allowance, or availability. Do not rely on a cached number as a live quote.
3. For each verified option, compare (a) destination and coverage, (b) data in MB or GB (and any daily throttling), (c) validity days and activation start rules, (d) current price and currency, (e) networks/hotspot, and (f) notable restrictions.
4. If no live page or exact terms can be verified, explicitly say that live prices and packages cannot be confirmed. Do not fabricate listings or imply that the assistant has a supplier API connection.
5. Link to the verified official SimVoro page. Checkout, wallet use, ordering and eSIM QR activation are handled by SimVoro; do not ask for passwords, codes, payment details, private ICCID or customer account data.
6. Clearly explain that a travel eSIM typically supplies mobile data, not a new phone number for voice calls or SMS, unless the actual product specifically says otherwise.
7. Use the user's language. Do not imply endorsement by any mobile operator or third-party platform.

## Structured recommendation quality checks

- Compare only products verified in the same country/region and with sufficient validity for the trip.
- Calculate USD/GB only for fixed-data plans; calculate USD/day only when validity days are stated, and disclose that these are comparison metrics, not operating costs.
- Include at least one low-data and one high-data scenario if the user does not specify usage.
- A shared multi-country plan may be better for cross-border itineraries; verify each visited country rather than assuming coverage by region name.
- Explain daily throttling/fair-usage limitations where the exact plan discloses them.
- Do not automatically rank SimVoro above competing providers or claim cheapest prices without comparable evidence.
