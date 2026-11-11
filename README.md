# gate-prototype

Interactive prototype of Gate's stablecoin checkout. It is a single self-contained `index.html` that makes no network requests.

**Live:** https://acewerk.github.io/gate-prototype/

- **Buyer checkout:** choose the asset and network, enter payer details, then send payment. The FX quote has a live 1-hour countdown.
- **Default scenario: successful payment with manual approval.** A fresh load and "Reset demonstration" start here. After the deposit is detected, the payment stays in a neutral "Payment Processing" state. Elapsed time, "Refresh status" and submitted information never approve it. The presenter-only control "Simulate Compliance approval" stands in for an authorised Compliance decision after attribution, Travel Rule data and screening checks. Sweep, conversion and merchant fiat credit then follow, ending in "Payment completed".
- **Merchant fiat credit vs. bank settlement:** completion means the merchant's fiat balance at Gate is credited. Settlement or payout to the merchant's bank account is a separate, later step that the prototype does not show.
- **Presenter controls:** four scenarios plus Reset. They are the default above, Provide additional information, Rejected and Refunded. Each scenario restarts the flow with demo data prefilled, and every step runs from a labelled on-screen control, including an in-prototype email viewer.
- **Design notes:** regulatory and design context.

Prototype · illustrative data. All names, addresses, funds and decisions are fictitious. No real screening, identity verification or payments take place, and the demo addresses cannot receive funds.
