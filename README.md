# Othello Vault — clickable prototype

Single-file HTML prototype of Othello Vault for Medcentric. Open `index.html` in a browser — no build step or dependencies.

**Sign in:** choose a view from the *View as* dropdown and use the demo password `Jupiter`. (The password is checked client-side — it keeps casual visitors out, it is not real security.)

## Views (switch any time from the *Viewing as* chip or the user menu)
- **Client Administrator** — Advice Areas (create, edit, permissions), providers and products, requirement rules from the Standard Document List (100 types), application form templates and field mapping, Vault settings, Team & Access (users, groups, permission matrix, access log), brand style switcher (Studio, Ledger, Pulse)
- **Advisor** — dashboard, Customers (the CRM: records and flagged details only), Applications, New Customer (Othello finds the customer's Drive folder, scans and matches every document, and asks the advisor to fix mismatches before the record is created), Vault
- **Team Member** — Customers, Flagged Details, Applications (checklists and application forms per accepted advice area), Vault
- **How It Works** — the end-to-end workflow walkthrough for the project team

## First-Time Setup Simulation
Start it from **Run First-Time Setup Simulation** on the sign-in screen (same password) or **Setup Simulation** in the nav. 23 steps:
1. **Workspace setup (Administrator)** — teams and people (roles Administrator / Lead / Member, job titles), organisation and brand (logo, business details, contacts, regional settings), Google Drive (no customers added), 5 advice areas, providers and products, document requirements, upload the real ANZ PDF forms, map their fields, go live
2. **Advisor (Lead)** — dashboard, find the customer in Drive (several folders match; the date of birth on the ID picks the right one), automatic scan and match, fix mismatches (hover any document to see the conflicting value), the customer record built from the Fact Find, Authority to Continue per area and the strategy pack's high-level recommendations, approve
3. **Credit team (Member)** — dashboard and queue, product and loan details, **populate the ANZ forms** (each field written live into the real PDFs in the browser with pdf-lib, previewed with pdf.js, hover any field for its value and source, download), checklist with custom documents and send to the customer, new files detected and flagged, customer application view

The four blank ANZ forms (cover sheet, applicant/guarantor declaration, statement of financial position, interview guide) are embedded; the PDF libraries load from cdnjs, so filling and previews need an internet connection.

Terminology follows the Othello Vault project scope: the **Client** is the advisory firm (Medcentric) and the **Customer** is the household being advised. Customers enter an advice area only after they sign an Authority to Continue for it.

All customer data and documents are fictional. Wealth products are mapped to the MC Wealth Services APL (13/04/2026).
