# Monero for Merchants: A Practical Guide for Real‑World Businesses: A Simple Getting-Started Guide

*Clear, friendly, and structured documentation for merchants, freelancers, and businesses who want to accept Monero (XMR) quickly and safely — without needing technical knowledge.*

---

## 📄 Monero Merchant Quickstart (1 Page)

### **1. Install a Wallet**

* Monerujo (Android)
* Cake Wallet (iOS/Android)

### **2. Back Up Your Wallet**

* Write down your 25-word recovery phrase on paper
* Store it somewhere safe (not on your phone)

### **3. Accept a Payment**

1. Open wallet
2. Tap **Receive**
3. Show the QR code to the customer
4. Customer scans & sends XMR
5. Wait ~20 seconds for **1 confirmation**

### **4. Track Sales (Optional)**

* Create a subaddress for each order or day
* Helps with accounting & organization

### **5. Move Funds to Savings**

* Keep large balances in a cold wallet (Feather or Monero GUI)
* Only keep spending money in your mobile wallet

---

## **Simple Payment Flow Diagram**

```
Customer → scans QR → sends XMR
                     ↓
Merchant wallet detects payment → shows confirmation
                     ↓
              Order completed
```

---

## **Beginner Mode vs Advanced Mode**

### **Beginner Mode (Most Shops)**

* ✔ Use a mobile wallet
* ✔ Show a QR code
* ✔ Accept payment after 1 confirmation
* ✔ No integration needed
* ✔ Fastest way to accept Monero

### **Advanced Mode (E-commerce / Tech-Savvy Users)**

* ✔ Use subaddresses for each order
* ✔ Automate payment detection
* ✔ Use monero-wallet-rpc
* ✔ Integrate with checkout pages

---

## 1. Introduction

### Quick Merchant Checklist (Fast Start)

If you don't want to read everything, start here:

* [ ] Install a Monero wallet (Monerujo or Cake Wallet)
* [ ] Write down your 25‑word recovery phrase on paper
* [ ] Open **Receive** → show QR code to customers
* [ ] Optional: Create subaddresses to track payments
* [ ] Accept payment → wait for 1 confirmation (~20 sec)
* [ ] Move larger earnings to a cold wallet
* [ ] Save this guide for later (security tips & advanced tools)

This checklist will appear again at the end for quick reference.
Monero (XMR) is a digital cash system built for privacy, security, and true financial independence. Unlike most cryptocurrencies, Monero payments are private by default, extremely low-fee, and ideal for real-world commerce.

### **Why merchants use Monero:**

* **Privacy:** Transaction details are hidden from competitors, suppliers, and attackers.
* **No chargebacks:** Payments are final (similar to cash).
* **Global & borderless:** Customers from anywhere can pay instantly.
* **Low fees:** Typically fractions of a cent.
* **Simple UX:** Customers just scan a QR code.
* **Works even where traditional banking fails:** Ideal for regions with unstable financial infrastructure.

This guide is written **for non-technical merchants**, small businesses, and freelancers who want to accept Monero easily and safely.

---

## 2. What You Need (Minimal Setup)

Accepting Monero does *not* require running a node or understanding cryptography. You just need a wallet.

### **Option A — Mobile Wallet (Recommended for Small Shops)**

These wallets are easy, user‑friendly, and safe:

* **Monerujo (Android)**
* **Cake Wallet (iOS & Android)**

These options are best for:

* Cafés
* Small retail stores
* Barbers
* Freelancers
* Anyone wanting a simple POS setup

**Set up steps:**

1. Install a wallet from the official app store.
2. Create a new wallet.
3. Write down the 25‑word recovery phrase (on paper, not your phone).
4. Set a strong PIN.

### **Option B — Desktop Wallet (For Larger Businesses)**

If you need more control and bookkeeping:

* **Feather Wallet** (recommended)
* **Official Monero GUI Wallet**

These allow:

* View-only wallets for accountants
* Creating many subaddresses for tracking payments
* Easier cold storage management

---

## 3. Accepting Payments (The Simple Way)

This is the fastest and easiest method with no technical work.

### **Step 1: Display Your Monero Address (QR Code)**

Every wallet can show a QR code for receiving payments.

To accept payments:

1. Open your wallet.
2. Tap **Receive**.
3. Show or print the QR code.
4. Customer scans → pays → done.

### **Step 2: Confirm the Payment**

Monero wallets show incoming payments quickly.

* First confirmation arrives in ~20 seconds.
* Most merchants accept payment after 1 confirmation.
* High‑value orders can wait a bit longer.

### **Step 3: Track Sales (Subaddresses)**

You can generate a **new subaddress** for each:

* Order
* Day
* Customer
* Product

This makes it easy to track what was paid for.

### **Step 4: Move Earnings to Cold Storage**

For long‑term savings:

* Use Feather or the official GUI wallet.
* Keep large balances offline.
* Back up your recovery phrase safely.

---

## 4. Accepting Payments (Advanced Merchant Options)

For businesses that want automation or website checkout.

### **Option A — Simple “Pay with Monero” Button**

You can embed a static payment button on your site.
It opens a QR code for customers to pay easily.

(This guide will later include a payment‑button generator.)

### **Option B — Payment Request Page**

Ideal for online stores.

* Customer opens a dedicated page.
* A **unique subaddress** is created for their order.
* Your business can detect payment automatically.

### **Option C — Full Wallet RPC Integration**

For developers or larger operations.
This allows you to:

* Create subaddresses programmatically
* Detect payments automatically
* Update orders

This guide will include beginner‑friendly explanations and starter templates.

---

## 5. Tools & Starter Kits

This guide will grow to include:

* QR/Payment button generator
* Python starter kit
* Flask integration template
* HTML donation page template
* Monero RPC cheat sheet
* Minimal POS scripts

All designed to be simple, safe, and easy to maintain.

---

## 6. Security Best Practices for Merchants

Keep your business and customers safe with these simple rules:

* **Never share your recovery phrase** with anyone.
* **Never type your seed phrase into a website or email.**
* **Use a view‑only wallet** for accountants.
* **Use subaddresses** to track individual orders.
* **Back up your wallet’s seed** on paper, not digitally.
* **Keep savings in cold storage** (secondary wallet).
* **Keep your wallet app updated** to the latest version.

---

## 7. Frequently Asked Questions

### **How do I issue a refund?**

Send Monero back to the customer’s address. No special tools needed.

### **Do I need to run a Monero node?**

No. Mobile wallets connect to remote nodes.

### **What are the fees?**

Usually tiny—fractions of a cent.

### **Can I accept Monero without a website?**

Yes — just show your QR code.

### **What if a customer pays the wrong amount?**

Ask them to send the difference. You can verify amounts in your wallet.

### **How do I convert to fiat?**

You may use P2P platforms or crypto exchanges depending on your local laws.

---

## 8. Real‑World Use Cases

* Coffee shops and restaurants
* Barbers and salons
* Online software sales
* Freelancers and consultants
* Market stalls and pop‑ups
* Nonprofits accepting donations
* Tourism and travel services

Monero is used globally, especially in regions with unstable banking.

---

## 9. Next Steps

Coming soon:

* A Merchant POS template
* Expanded documentation

If you want to contribute, improve the guide, or request features, join the Monero community or contact the maintainers of this project.

---

*This guide will continue to grow — thanks for helping build real-world Monero adoption!*
