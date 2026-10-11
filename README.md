# RationSaathi

RationSaathi is a browser-only prototype for the VORTEXA 3.0 P-01 RationSaathi problem. It demonstrates an entitlement calculation, delivery records with evidence references, and a neutral discrepancy report.

## Run the demo

Open `index.html` in a modern browser. No installation or server is required.

## Demo accounts

All demo accounts use the password `anna123`:

| Role | Demo account |
| --- | --- |
| Beneficiary | `beneficiary@demo` |
| Ration shopkeeper | `shop@demo` |
| Department reviewer | `department@demo` |

Start with the shopkeeper account and add a distribution for `SAMPLE-001`. Sign out, open the beneficiary account, review the calculation, and submit a report. To see the receipt-text assistant, paste fictional evidence text and choose **Analyze text**; review and confirm its category/date/quantity suggestions before adding a delivery. Sign out again and open the department account to review the submitted report.

The receipt assistant uses a small offline Naive Bayes classifier trained on example phrases included in the page. It also looks for common date and kilogram patterns. These are suggestions only: the displayed score is not a probability, users must review the original evidence, and only manually entered/confirmed rule and delivery values are used for arithmetic.

## Prototype limits

- Sign-in is simulated in browser code. It is not secure authentication and must not be used for real accounts.
- Data is saved in browser local storage, so it is available only in the same browser profile and device.
- Use fictional data only. Do not enter Aadhaar numbers, passwords used elsewhere, or real beneficiary records.
- The receipt-text classifier and date/quantity pattern matching are a lightweight local demo, not a production AI service.
- There is no server-side storage or cross-device synchronization.

## Project files

- `index.html` — complete single-page demo (HTML, CSS, and JavaScript)
- `.gitignore` — ignores local secrets and editor/system files



