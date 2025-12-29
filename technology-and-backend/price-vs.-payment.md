---
title: "Price vs. Payment"
description: "Understanding the flexible currency conversion and settlement logic within the Mesi ecosystem."
---

Mesi provides a flexible payment infrastructure that bridges traditional finance and the Creator Chain. Users can list content in one currency while supporters pay in another, with the platform handling the underlying conversion seamlessly.

## 1. Same-Format Payments
This represents a direct transaction where the **Price Currency** matches the **Payment Method**. These transactions are typically faster and involve no conversion spread.



* **Fiat Pricing:** (e.g., USD) → Paid via Credit Card / Apple Pay.
* **Stablecoin Pricing:** (e.g., USDC) → Paid via Stablecoin Wallet.
* **Native Token Pricing:** (\$MESI) → Paid via **\$MESI** tokens.

---

## 2. Mixed-Format Payments
Mixed-format payments allow for maximum accessibility. A fan can use traditional currency to purchase an item priced in crypto, or vice-versa. Mesi’s backend automatically calculates the exchange rate at the moment of the transaction.



Common mixed-format scenarios include:

| Pricing Currency | Payment Method | Use Case |
| :--- | :--- | :--- |
| **Fiat** | **\$MESI** / Stablecoins | Fans using tokens to buy items priced in USD. |
| **Fiat** | Stablecoins | Using digital dollars for traditional pricing. |
| **Stablecoins** | **\$MESI** | Swapping digital assets for stable-priced content. |
| **\$MESI** | Fiat | New users buying token-priced NFTs with a credit card. |
| **\$MESI** | Stablecoins | Institutional or large-scale purchases of token-priced assets. |
| **Stablecoins** | Fiat | Simplified onboarding for stable-priced premium features. |

---

## The Settlement Standard

Regardless of the "Price vs. Payment" combination chosen at the point of sale, the Mesi platform follows a unified settlement protocol to ensure creators can easily manage their earnings.

<Card title="Creator Settlement" icon="bridge" color="#3b82f6">
  While fans enjoy the flexibility of **Mixed-Format Payments**, all final settlements to the creator's platform wallet are executed in **\$MESI** tokens. This maintains the utility and demand for the native ecosystem currency.
</Card>

<Note>
  **Exchange Rates:** For all mixed-format payments, Mesi utilizes real-time price oracles to ensure that the creator receives the exact value of the listed price in **\$MESI** at the time of the transaction.
</Note>

<Tip>
  **Listing Strategy:** Creators are encouraged to list high-ticket items in Stablecoins or Fiat to protect against volatility, while using **\$MESI** pricing for community-centric rewards and engagement-based content.
</Tip>
