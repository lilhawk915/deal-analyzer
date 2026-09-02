# Deal Analyzer

Single-page flip and wholesale underwriting calculator. No dependencies, no build step,
no backend — one self-contained `index.html`.

## Use it

Open the published page, enter the deal, and results update as you type. Entries are
saved to your own browser (localStorage) and restored on your next visit; "Reset
defaults" clears them. Nothing is sent to a server.

## What it calculates

- Net profit, total-cost ROI, purchase+rehab ROI, annualized ROI
- Financing costs (points + interest on first / second / other loans)
- Holding costs (taxes, insurance, HOA, utilities, misc — monthly x hold time)
- Buying and selling costs
- Down payment at closing and committed capital (cash in, net of loans)
- Maximum allowable offer using the 70% or 75% rule

## Editing

Everything lives in `index.html`. The `defaults` object near the top of the `<script>`
block sets the starting values for every field.
