---
name: b300-price-check
description: Research current NVIDIA B300 GPU rental and purchase offers and report the lowest and highest verified comparable prices, availability, locations, total costs, and provider credibility. Use when the user asks for B300 prices or a B300 market price check.
---

# B300 price check

Check live sources on every invocation. By default cover both rentals and purchases worldwide, reporting USD while preserving original currencies. Honor narrower scope requested by the user. There is no licensing or authorization-certification filter and no preset budget cap. This skill runs when requested; it does not schedule monitoring.

## Research

Search broadly for rental providers and hardware sellers, then open the underlying provider or seller pages. Prefer current product listings, pricing pages, stock dashboards, and published quotes over aggregators, search snippets, or marketing articles. Use aggregators for discovery. Do not treat snippet-only prices as verified. Record the actual date, time, and timezone checked. Check price effective dates: exclude future scheduled rates from current ranges and flag upcoming changes separately. Distinguish current sale prices from crossed-out former prices. If live browsing is unavailable, say current prices cannot be verified rather than presenting remembered prices as current.

Confirm each offer explicitly identifies NVIDIA B300 hardware, GPU count, memory where published, and the purchasable or rentable unit. Do not silently substitute B200, H200, GB300 systems, or vague Blackwell listings. Keep GB300 systems separate if useful and label the distinction. Distinguish an individual GPU or module from a baseboard, complete server, or rack. Record significant configuration differences.

For every usable offer collect:
- Provider/seller name, direct source link, and evidence of company identity and hardware details. Describe credibility using observable evidence, not an unsupported endorsement; mark unverified claims.
- Provider country and physical hosting region for rentals, separately. For purchases record seller/shipping origin and delivery region if available. Never infer hosting location from headquarters.
- Published price, currency, billing unit, GPU count, and pricing conditions.
- Availability: explicitly available now, preorder/backorder, waitlist, quote-only, advertised with availability unconfirmed, or unavailable. Attribute stock claims to the source; a public claim is not a checkout confirmation.
- Minimum rental duration, minimum GPU/server quantity, deposit or prepayment, and contract commitment.
- Extra costs such as storage, network egress, setup, taxes, shipping, and support when disclosed. Mark unknown charges as unknown, not zero. Distinguish refundable deposits from expenses while noting upfront cash required.

## Compare like with like

Separate rental groups: on-demand, spot/interruptible, and reserved or long-term contracts. Preserve full-node hourly prices and normalize to USD/GPU/hour only when the GPU count and billing basis are explicit. Explain the calculation and minimum actual spend; an eight-GPU server divided by eight is not a single-GPU rental offer. For monthly contracts show the original monthly price and disclose any assumed billable-hour conversion.

Separate purchase groups: individual GPU/module, baseboard, complete server, and rack; distinguish new, used, and refurbished condition. Report full system prices directly. A calculated system-price-per-GPU includes other components and must not enter a standalone GPU price range.

Keep conditional 'from' prices, unconfirmed availability, preorders, and quote-only offers apart from verified orderable offers. Do not invent numeric prices for quote-only listings. Use a current cited exchange rate if conversion is needed, with its date and the original amount.

Within each comparable group identify the lowest and highest verified prices found and their providers. State that these are observed search results, not guaranteed global market extremes. If only one qualifying offer exists, say so rather than implying a broad range; if none exist, say no verified public range is available. Do not use stale, unrelated, suspicious, or unverified listings to manufacture a minimum or maximum. Deduplicate syndicated offers. Explain material exclusions briefly.

Search multiple independent providers and sellers in both categories. Follow up on unusually low/high offers and ambiguous units. Stop when further targeted searches add no materially different verified offers, and disclose coverage gaps. Never purchase, reserve hardware, open accounts, or contact providers merely to run this skill.

## Vera Rubin updates

Also monitor and research current NVIDIA Vera Rubin platform developments and market availability using the same verification standards used for B300 research.

On every relevant invocation:

- Check current official NVIDIA announcements and reliable provider, OEM, cloud, and infrastructure sources for Vera Rubin-related updates.
- Track announced Rubin GPU products, Vera CPU + Rubin GPU systems, complete servers, racks, cloud instances, and other commercially relevant configurations separately.
- Do not treat roadmap announcements, expected launch windows, or future availability as products that can already be rented or purchased.
- Clearly distinguish:
  - officially announced products
  - upcoming products
  - preorder or reservation offers
  - quote-only offers
  - publicly orderable products
  - actually available rental capacity
- Record exact product names, GPU counts, memory, system configuration, availability date, region, and pricing when published.
- Do not silently substitute B300, B200, GB300, H200, or other Blackwell products for Vera Rubin products.
- Keep individual GPU/module pricing separate from full server, rack, and cloud-instance pricing.
- For rentals, separate on-demand, reserved, long-term, and interruptible pricing when applicable.
- For purchases, separate individual components, complete servers, racks, and integrated systems.
- When pricing is unavailable, report "price not publicly disclosed" rather than estimating or inventing a number.
- Verify unusually low or high prices using direct provider or seller sources whenever possible.
- Record the date and time checked and clearly label information that is based on roadmap announcements rather than current commercial availability.

When both B300 and Vera Rubin information are requested, report them in separate sections and do not mix their price ranges.

Where useful, explain how Vera Rubin differs from B300 or other current-generation NVIDIA data-center products, but only use current verified specifications and clearly separate confirmed facts from announced future specifications.

The goal is to provide a reliable view of:
1. current Vera Rubin product and platform announcements,
2. expected commercial availability,
3. verified rental or purchase offers when they exist,
4. published prices and contract terms,
5. provider and geographic availability,
6. major changes since the previous check.

## Report

Lead with the checked timestamp and a compact summary of verified rental and purchase ranges by comparable group. Provide linked comparison tables with hardware/unit, price and terms, availability, location, and total-cost caveats. Keep rental and purchase tables separate. Include minimum commitments, extra charges, and provider credibility notes in the table or concise linked notes. Clearly distinguish verified facts, provider claims, calculations, and unknowns. End with the most important limitations or information needed to obtain firmer quotes. Do not recommend a winner solely because it has the lowest headline price.

