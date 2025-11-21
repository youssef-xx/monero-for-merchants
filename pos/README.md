Monero POS Template (HTML + JavaScript)

A simple, browser-based point-of-sale screen for merchants who want a clean and fast way to accept Monero (XMR).
This POS template requires no server, no installation, and no technical setup. It runs entirely in the browser as a single HTML file.

What This POS Template Is

This tool provides a dedicated checkout-style screen for taking Monero payments. It removes unnecessary wallet features and keeps the focus on a fast, simple workflow:

Enter an amount

Generate a payment QR code

Customer scans and pays

Merchant confirms payment in their wallet

Mark the order as paid manually

It is designed for cafés, small retail shops, barbers, freelancers, market stalls, and anyone who wants a minimal Monero payment interface at the counter.

What It Can Do

Save the merchant’s Monero receiving address locally (browser storage)

Accept an amount in XMR and an optional label (e.g., “Order #12”)

Generate a valid monero: payment URI

Display a clean, large QR code for the customer

Provide a simple “copy payment URI” option

Work offline once opened in a browser

This file is safe to use because it does not interact with private keys or connect to any wallet.

What It Does Not Do (Important)

This POS template does not:

Detect on-chain payments automatically

Connect to monero-wallet-rpc

Verify confirmations

Handle private keys

Generate subaddresses

Calculate fiat conversion

These features require server-side code or wallet RPC access, which would add complexity and, in some cases, security risk.
This template stays intentionally simple so it can be used safely by any non-technical merchant.

How To Use

Download monero-pos.html

Open it in any modern browser (Chrome, Firefox, Safari, Brave)

Paste your Monero receiving address into the address field

Press “Save” to store it locally

Enter the XMR amount for the payment

Press “Generate Payment QR”

Show the QR code to the customer for scanning

Merchants can keep this page open on a phone or tablet at the checkout counter.

Design Approach

The template is intentionally clean, simple, and neutral:

Minimal layout

Large buttons

Friendly spacing

Subtle micro-interactions

No clutter

The goal is to make Monero payments approachable and easy to use for everyday staff and customers.

For Developers

Because this POS is built as a single stand-alone HTML file, it can be extended easily. Developers may choose to:

Add fiat-to-XMR auto-conversion

Add automatic subaddress generation (via RPC)

Add payment polling or automatic “paid” detection

Integrate the template into a broader checkout system

The file is intentionally simple and readable for this purpose.

Files
pos/
└── monero-pos.html

Contributing

Improvements to the template are welcome.
You can submit issues or pull requests with enhancements, usability fixes, or developer extensions.
