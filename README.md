# 2980 Budd Road, Stockbridge MI — Pre-Inspection Due-Diligence Report

A public-records due-diligence report for a property purchase in Stockbridge, Michigan. Compiled from deeds, court filings, tax-foreclosure publications, environmental databases, FEMA maps, and the EGLE well log.

**Live site:** [open `index.html` in a browser](index.html) — also hosted via GitHub Pages once the repo is published.

## What's in this folder

### Web report
- **`index.html`** — single-file HTML report. Open in any modern browser. Mobile-friendly. Print-friendly.

### Reference markdown documents
- **`REPORT.md`** — full source-cited report (the underlying detailed write-up the website was built from).
- **`deed_index_findings.md`** — tabulated chain of recorded deeds, mortgages, and tax-related instruments from the Ingham County Fidlar deed index.
- **`INDEX.md`** — file inventory + paywalled-records list + phone-call list.

### Saved primary-source artifacts (in repo)
- `ingham_2025_tax_insert_publication.pdf` — Ingham County 2025 tax-foreclosure show-cause publication (lists this parcel as $7,800.17 delinquent).
- `ingham_auction_*.pdf` — five Ingham County tax-foreclosure auction result PDFs (Aug 2022, Oct 2022, Aug 2023, Oct 2023, Oct 2024). The parcel does not appear in any of these — confirms the property was *not* tax-auctioned 2022-2024.

### FEMA flood-map artifacts (NOT in repo — excluded for size)

The 89 MB of FEMA artifacts (`FEMA_FIRM_panel_26065C0425D.png`, `.pgw`, `.zip`, `FEMA_FIRM_README.pdf`) are listed in `.gitignore` and not pushed to GitHub. The web report links directly to FEMA's interactive Map Service Center viewer instead — that gives crisp parcel-level zoom which a static image embedded in a browser can't match. To re-download the static panel: visit https://msc.fema.gov/portal/search?AddressQuery=2980+Budd+Road+Stockbridge+MI+49285 and click "Map Image &rarr; Download FIRM Panel".

## How to read the report

The website uses color-coded badges for confidence:

- 🟢 **Confirmed** — verified against a primary public-records source
- 🟡 **Estimate** — a range or model; verify with the local agent or assessor
- 🔵 **Recommendation** — an action you should take
- 🟠 **Assumption** — an inference the analyst drew that isn't directly verified
- 🟣 **Open question** — something not known; needs to be answered before closing

Underlined dotted text on the website has a tooltip definition for legal/technical jargon. Hover (desktop) or tap (mobile) to read.

## Critical action items

The website's "Critical action items" section lists five things to do inside the inspection contingency window. Top three:

1. **Verify the 2026 tax-foreclosure was redeemed for THIS specific parcel** — title company should pull the redemption document from Tapestry (~$10) and confirm parcel `33-16-16-04-400-023` is in the legal description.
2. **Confirm the $67,500 seller-financed mortgage to the Hawkins Trust has been discharged** — title company orders the payoff letter.
3. **Order radon, arsenic, and full water-quality tests** — Ingham County is one of MI's worst for natural arsenic; deep bedrock well + Michigan basement is a textbook radon profile.

## Hosting on GitHub Pages

This folder is structured to be a self-contained GitHub Pages site:

1. Push this folder to a GitHub repository.
2. In the repo's Settings → Pages, set Source = `main` branch / `/ (root)`.
3. Wait ~60 seconds; the site will be live at `https://<username>.github.io/<repo-name>/`.

`index.html` is at the root, so it serves automatically. All asset paths are relative.

## Editing the report

The single-file HTML is editable in any text editor. To update something:

1. Open `index.html` in a text editor (VS Code, Sublime, BBEdit, etc.).
2. Find the section you want to update (sections are clearly commented with `<section id="...">`).
3. Save and commit.

To update markdown reference docs, edit `REPORT.md`, `deed_index_findings.md`, or `INDEX.md` directly.

## License / use

This is a personal due-diligence report compiled for one specific property purchase. It is not legal, financial, or professional advice. Information was current as of 2026-05-04. Verify everything with your title company, inspector, and attorney before closing.
