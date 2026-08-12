# GLS Seminars Account Audit — Interactive Deliverable

Post migration verification audit for GLS Seminars, delivered by QuikFire.

## Files

| File | What it is |
|---|---|
| `index.html` | **Deploy this.** Single self-contained page, all styles, scripts, fonts, and the logo inlined. Works offline and from any static host. |
| `GLS Seminars Audit.dc.html` | Editable source. Open in Claude Design to change content or layout, then re-bundle to `index.html`. |
| `support.js` | Runtime required by the source file. Not needed by `index.html`. |
| `assets/quikfire-logo.png` | QuikFire logo, used in the header and footer. |

## Deploying

Static hosting, no build step. Push to a repo and point GitHub Pages / Netlify / Vercel at the root; `index.html` is the entry point. Embeddable later in a client portal as-is.

## Content structure

All findings data lives in the logic class at the top of `GLS Seminars Audit.dc.html` as plain arrays: `FINDINGS`, `POSITIVES`, `JOURNEYS`, `SCORECARD`, `PHASES`, `NOTES`. Edit those arrays to update the page. The same shape carries forward to the next client audit.

## Confirm before publish

- Draft severity ratings on the findings
- Draft impact and effort values in the priority matrix
- Draft scorecard ratings
- Executive summary block, keep or cut
- QC pass on all client facing copy

No pricing appears in this deliverable by design. Investment is discussed after the review call.
