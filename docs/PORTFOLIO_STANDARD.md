# Portfolio publishing standard

This repository is the **public identity and product-portfolio layer** for Yordan Bozhkov. It is not the development source of truth and must not be used to ship or version live product code.

## Status terminology

| Label | Meaning | Portfolio treatment |
| --- | --- | --- |
| Exploration | Research, sketches, hypotheses or conceptual design | Brief mention only; avoid implying functionality |
| Interactive prototype | Demonstrable experience, but not an accepted product release | Clearly labeled prototype; no production claims |
| In development | Working implementation undergoing engineering or product iteration | Workbench card; no commercial availability claims |
| Release improvements | A release candidate or local build requiring further review | State the known limitation plainly |
| Released | Owner-approved, publicly shareable product | Eligible for a full public showcase, with tested claims |

A successful build or test suite is not sufficient to claim *Released*. Require evidence of key user journeys, real product screens, owner acceptance and a truthful list of limitations.

## Publish gate

Before creating a public product showcase, verify:

1. Product name and outward-facing description are approved.
2. Release and distribution status are accurately documented.
3. Screenshots come from the actual approved software, not concept art presented as implementation.
4. Testimonials, users, adoption metrics, uptime, badges and performance claims have verifiable sources or are omitted.
5. No secrets, customer data, personal information, internal logs, credentials, licensed art or proprietary code are included.
6. Links point to real public websites, demos or documentation; do not add placeholders as if live.
7. The owner approves publication.

## Structure

- This repository: personal identity, curated workbench, navigation.
- Future `product-name` repositories: **portfolio case studies**, not build mirrors.
- Development: remains in original local or private environment.

## Artwork

The SVG covers in `assets/` are **custom editorial illustrations**, *not* screenshots or representations of current running interfaces. Replace with approved product captures only after release review.

## Future release workflow

1. Confirm the release gate and approved screenshots.
2. Copy `docs/PRODUCT_SHOWCASE_TEMPLATE.md` into a new public portfolio repository's README.
3. Replace every placeholder with product-specific verified facts.
4. Publish only approved artwork, screenshot and product copy.
5. Link from the personal profile and pin the strongest public showcases.
6. Refresh only when meaningful changes or releases occur. No synthetic contribution statistics.
