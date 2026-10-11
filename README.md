# RationSaathi

RationSaathi is a browser-only prototype for the VORTEXA 3.0 P-01 ration entitlement and delivery-evidence workflow. It has separate workspaces for ration card holders, Fair Price Shop dealers, and department officials.

## Open the demo

Open `index.html` in a modern browser. No installation or server is required. Choose a role, then sign in with its demo username and the shared demo password `anna123`:

| Workspace | Demo username |
| --- | --- |
| Ration Card Holder / Beneficiary | `beneficiary@demo` |
| Fair Price Shop Dealer | `shop@demo` |
| Department Official | `department@demo` |

The role dashboards link to household details and a clearly marked sample e-Ration card, entitlement and calculation, delivery history, reports, receipt-text suggestions, shop distribution records and responses, and department monitoring, evidence review, case management, and discrepancy analysis. The English/Hindi toggle translates the main navigation and common interface labels.

## Suggested demo flow

1. Sign in as `shop@demo` and add a dated distribution for household `SAMPLE-001`, including a fictional receipt reference.
2. Sign in as `beneficiary@demo`. Review the entered entitlement rule and delivery history, then create a partial delivery record or try the receipt-text helper. Confirm all suggestions and values before saving.
3. Submit a report for department review. Comparison labels distinguish **Potential shortfall**, **Exact match**, and **Above entered entitlement**. A difference is not a fraud finding; the report says that its cause is undetermined.
4. Sign in as `shop@demo` to add a factual response, and as `department@demo` to review evidence, update case status, and see comparison counts.

The default demo rule is fictional: 5 kg per household member for four members. Confirm the actual applicable entitlement with an authoritative source before using any real figures. The receipt helper uses simple local keyword and pattern matching; suggestions are not probabilities and never change calculation arithmetic.

## Prototype limitations

- Sign-in is simulated in browser code and is not secure authentication.
- Records are stored in local storage in this browser profile only. They do not sync across devices or users.
- Use fictional information only. Do not enter Aadhaar numbers, real beneficiary records, or passwords used elsewhere.
- The sample e-Ration card is illustrative and is not an official card. This prototype is not an official government service.

## Project files

- `index.html` — the single-page demo, including its styling and browser-side interactions.
- `.gitignore` — ignores local secrets and editor/system files.
