# Othello Vault — clickable prototype

Single-file HTML prototype of Othello Vault for Medcentric. Open `index.html` in a browser — no build step or dependencies.

**Sign in:** choose a view from the *View as* dropdown and use the demo password `Jupiter`. (The password is checked client-side — it keeps casual visitors out, it is not real security.)

## Views (switch any time from the *Viewing as* chip or the user menu)
- **Client Administrator** — Advice Areas (create, edit, permissions), providers and products, requirement rules from the Standard Document List (100 types), application form templates and field mapping, Vault settings, Team & Access (users, groups, permission matrix, access log), brand style switcher (Studio, Ledger, Pulse)
- **Advisor** — dashboard, Customers (the CRM: records and flagged details only), Applications, New Customer (Othello finds the customer's Drive folder, scans and matches every document, and asks the advisor to fix mismatches before the record is created), Vault
- **Team Member** — Customers, Flagged Details, Applications (checklists and application forms per accepted advice area), Vault
- **How It Works** — the end-to-end workflow walkthrough for the project team

## First-Time Setup Simulation
Start it from **Run First-Time Setup Simulation** on the sign-in screen (same password) or **Setup Simulation** in the nav. 27 steps across six groups:
1. **Workspace setup (David Le, Administrator)** — teams and people (multi-select team membership), organisation and brand (Medcentric logo), the centralised Medcentric Clients shared drive (personal folders excluded), advice areas, providers and products with their PDF forms (Westpac, Macquarie, Acenda, HUB24, Macquarie CMA), document requirements picked from the Standard Document List (clients request new types rather than adding them), field mapping (Customer record, Fact Find, a supporting document and its field, and more), go live
2. **Advisor (Mina Andrawis)** — dashboard, find the customer in Drive, scan and match, fix mismatches (including income: Fact Find against the ATO income statement), the customer record (as-of date and source on every attribute, a timestamped change log, and a future-scope timeline with Record a Change in Position), approve
3. **Credit team** — product and loan details (customer-specific document types), **Forms & Checklist**: the checklist is built from the files found in Drive, the Westpac and Macquarie forms fill live in the browser, fields waiting on a missing document are flagged, and progress shows for the checklist, the request and each form; new files detected, customer application
4. **Insurance team** — Acenda servicing-rights letter generated from the template, cover email
5. **Wealth team** — HUB24 Change of Adviser, HUB24 Change of Details, Macquarie CMA authority
6. **Two Weeks Later** — Westpac publishes a new form version: mappings carry over, new and renamed fields are flagged for review and approval, then the forms refill

The blank provider forms are embedded with adviser details removed; the PDF libraries load from cdnjs, so filling and previews need an internet connection.

Terminology follows the Othello Vault project scope: the **Client** is the advisory firm (Medcentric) and the **Customer** is the household being advised. Customers enter an advice area only after they sign an Authority to Continue for it.

All customer data and documents are fictional. Wealth products are mapped to the MC Wealth Services APL (13/04/2026).
