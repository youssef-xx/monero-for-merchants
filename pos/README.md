# Monero POS Template (HTML + JavaScript)

A simple, browser-based point-of-sale screen for merchants who want a clean and fast way to accept Monero (XMR). This POS template requires no server, no installation, and no technical setup. It runs entirely in the browser as a single HTML file.

## What This POS Template Is

This tool provides a dedicated checkout-style screen for taking Monero payments. It removes unnecessary wallet features and keeps the focus on a fast, simple workflow:

1. Enter an amount  
2. Generate a payment QR code  
3. Customer scans and pays  
4. Merchant confirms payment in their wallet  
5. Mark the order as paid manually

It is designed for cafés, small retail shops, barbers, freelancers, market stalls, and any business that wants a straightforward Monero payment interface at the counter.

## What It Can Do

- Save the merchant’s Monero receiving address locally (browser storage)
- Accept an amount in XMR and an optional label (e.g., “Order #12”)
- Generate a valid monero: payment URI
- Display a large QR code for the customer
- Provide a copy-to-clipboard button for the URI
- Work offline once opened in a browser
- Operate without exposing private keys or communicating with a wallet

## What It Does Not Do

This template intentionally avoids advanced features that require backend infrastructure or wallet RPC access. It does **not**:

- Detect on-chain payments automatically  
- Poll or connect to monero-wallet-rpc  
- Verify transaction confirmations  
- Generate subaddresses programmatically  
- Handle private keys  
- Convert fiat prices to XMR  

These features would require additional software and security considerations. This file stays intentionally simple so any merchant can use it safely.

## How To Use

1. Download `monero-pos.html`  
2. Open it in any modern browser (Chrome, Firefox, Safari, Brave)  
3. Paste your Monero receiving address into the address field  
4. Click “Save” to store it locally in the browser  
5. Enter the XMR amount for the payment  
6. Click “Generate Payment QR”  
7. Show the QR code to the customer for scanning  

This workflow can be used on a phone, tablet, or desktop computer. The page can remain open all day at a checkout counter.

## Design Approach

The template is intentionally clean, minimal, and easy to use. It uses:

- Large, easy-to-tap buttons  
- Clear input fields  
- A simple layout with no distractions  
- Subtle micro-interactions for clarity  
- A readable, neutral color scheme  

The goal is to make Monero payments feel straightforward for employees and customers, even without technical knowledge.

## For Developers

This POS is a fully client-side HTML file. Developers can extend it easily by adding features such as:

- Fiat-to-XMR conversion  
- Automatic subaddress creation via monero-wallet-rpc  
- Payment polling for automatic “paid” status  
- Integration with a broader checkout or invoicing system  

Its simplicity makes it a good starting point for custom merchant tools.

## Files

