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

## Report

Lead with the checked timestamp and a compact summary of verified rental and purchase ranges by comparable group. Provide linked comparison tables with hardware/unit, price and terms, availability, location, and total-cost caveats. Keep rental and purchase tables separate. Include minimum commitments, extra charges, and provider credibility notes in the table or concise linked notes. Clearly distinguish verified facts, provider claims, calculations, and unknowns. End with the most important limitations or information needed to obtain firmer quotes. Do not recommend a winner solely because it has the lowest headline price.
