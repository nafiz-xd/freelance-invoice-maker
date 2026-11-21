# Freelance Invoice Maker

A single-page invoice builder for freelancers. Fill in your details on the editor desk and watch a clean, paper-style invoice update live — then save it, track whether it has been paid, and print or export it as a PDF. Everything runs in the browser and is stored locally with localStorage, so no account or server is needed.

**Live demo: https://nafiz-xd.github.io/freelance-invoice-maker/**

## Features

- Live paper invoice preview that updates on every keystroke, styled like a real A4 document on a slate desk
- Your info (name/business, email, phone, address, payment note such as a bKash number) saved automatically to localStorage
- Client manager — save, select, and delete clients; selecting a client fills in the invoice's Billed-To section
- Auto-incrementing invoice numbers (editable), issue date and due date (defaulting to today and +7 days)
- Currency toggle between BDT (৳) and USD ($), with an optional exchange-rate field that shows an approximate BDT total on USD invoices
- Line items with description, quantity, and rate — amounts, subtotal, discount %, tax %, and grand total calculated automatically
- Invoice history — save invoice snapshots, toggle Paid/Unpaid status, delete entries, and click any entry to reload it into the editor
- Print / Save PDF button with dedicated print styles, so only the clean invoice prints on A4

## Tech

- HTML
- CSS (responsive grid layout, `@media print` styles, Google Fonts — Fraunces serif + JetBrains Mono)
- Vanilla JavaScript
- localStorage (`invme_profile`, `invme_clients`, `invme_history`, `invme_nextno`)

---
Built by Nafiz Bin Azad
