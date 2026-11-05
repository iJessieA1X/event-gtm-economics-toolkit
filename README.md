# Event GTM Economics Toolkit

A reusable Markdown and CSV kit for reviewing one event's cash flows, resources, audience, product use and unit economics. It works for launches, workshops, pop-ups and conferences, including AI products with metered API usage.

## Use it

1. Copy [`Event_GTM_Finance_Review_Template.md`](Event_GTM_Finance_Review_Template.md) for one event. Set the event window, timezone, owner and intended decision before collecting numbers.
2. Inventory authorized source records. Put line items in `cost_lines.csv`, observations in `metric_observations.csv`, and source references in `sources.csv` using the headers under `csv/`.
3. Reconcile each material figure to its source, population, time window and status. Leave unsupported amounts blank. Record missing evidence and owners.
4. Calculate only ratios whose numerator and denominator share a compatible scope. Keep cash cost, refundable deposits, asset allocation and opportunity cost separate.
5. Review the result privately before any sharing. Replace real team figures with synthetic examples if demonstrating the method publicly.

## Evidence and status

E1 = system export or ledger; E2 = contemporaneous receipt/contract; E3 = execution record; E4 = retrospective report; E5 = estimate/inference. `Verified` means both the source and the metric's scope have been checked. `Partially verified`, `Estimated`, `Pending`, `Unavailable` and `Not applicable` retain their literal meanings. Never promote E4/E5 to a confirmed transaction or causal result.

## Analysis rules

- A cash budget is funding, not revenue. Free venue/equipment is an in-kind resource, not cash expense.
- A deposit is separate from final cost. A reusable asset can have a purchase outflow and a different event allocation.
- Events, requests, sessions, devices, distinct users, attendees and printed items are different units.
- An event occurring after a campaign is a correlation until attribution can be demonstrated.
- If revenue or attributed value is absent, report cost efficiency and product outcomes without a financial ROI percentage.
- Do not collect API keys, raw user conversations or personal data in this toolkit.

## Suggested repository placement in a product team

Add this generic template at `docs/gtm/Event_GTM_Finance_Review_Template.md` and link it from a short `docs/gtm/README.md`. Keep completed event reviews in an access-controlled location chosen by the team.

## Provenance and license

Adapted from a user-authored brief and an AI-assisted v1.0 template in November 2026. © 2026 Jessie Ai. The text and blank CSV schemas in this repository are licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You may share and adapt them with attribution, a link to the license, and an indication of changes.
