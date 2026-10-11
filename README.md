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

Start with the shopkeeper account and add a distribution for `SAMPLE-001`. Sign out, open the beneficiary account, review the calculation, and submit a report. Sign out again and open the department account to review the submitted report.

## Prototype limits

- Sign-in is simulated in browser code. It is not secure authentication and must not be used for real accounts.
- Data is saved in browser local storage, so it is available only in the same browser profile and device.
- Use fictional data only. Do not enter Aadhaar numbers, passwords used elsewhere, or real beneficiary records.
- The current build does not yet include receipt-text AI suggestions or server-side storage.

## Project files

- `index.html` — complete single-page demo (HTML, CSS, and JavaScript)
- `.gitignore` — ignores local secrets and editor/system files



