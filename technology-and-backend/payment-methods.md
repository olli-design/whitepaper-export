---
title: "Payment Methods"
description: "Cross-platform payment infrastructure for Mesi Web and Mobile environments."
---

Mesi utilizes a hybrid payment architecture designed to balance blockchain efficiency with the accessibility of traditional mobile app stores. While the **Web App** serves as the primary hub for native $MESI token utility, the **Mobile App** leverages In-App Purchases (IAP) to remain compliant with Apple and Google ecosystem requirements.

## Platform Payment Matrix

The table below details how transactions are handled across different environments. 

| Feature | Mobile App (iOS/Android) | Web App (Desktop/Mobile Web) |
| :--- | :--- | :--- |
| **Bid to Meet (BTM)** | In-App Purchase (IAP) | $MESI Token |
| **Buy/Sell NFTs** | In-App Purchase (IAP) | $MESI Token |
| **Live Tipping** | In-App Purchase (IAP) | $MESI Token |
| **Private Messaging** | In-App Purchase (IAP) | $MESI Token |
| **Subscriptions** | In-App Purchase (IAP) | $MESI Token |
| **Affiliate Marketing** | Apple / Google Pay | $MESI Token |
| **AI Premium Tools** | In-App Purchase (IAP) | $MESI Token |
| **Acquiring $MESI** | In-App Purchase (IAP) | Credit Card / Bank Wire |



---

## The Unified Settlement Model

Mesi maintains a unified economic backend regardless of the user's payment front-end. This ensures that creators always receive a consistent asset type.

<Card title="Withdrawal Standard" icon="wallet" color="#3b82f6">
  All platform withdrawals are settled exclusively in **\$MESI** tokens. Whether a fan pays via Apple Pay on mobile or **\$MESI** on the web, the underlying value is converted and settled to the creator's wallet as **\$MESI**.
</Card>

---

## Strategic Implementation

### Mobile Environment (IAP)
Mobile payments are processed via the native app store billing systems. This provides:
* **Frictionless Onboarding:** Fans can support creators using saved credit cards or biometrics.
* **Global Compliance:** Adheres to strict mobile marketplace policies.
* **Automatic Conversion:** Mesi handles the backend logic to ensure IAP payments contribute to the creator's tokenized revenue.

### Web Environment (Native Token)
The Web App offers the most direct interaction with the **Creator Chain**.
* **Lower Fees:** Bypasses mobile app store commissions.
* **Instant Settlement:** Direct peer-to-peer blockchain transactions.
* **Advanced DeFi:** Integration with $MESI staking, locking, and micro-loans.

<Tip>
  **For Power Users:** Using the Web App for high-value transactions or bulk NFT purchases is generally more cost-effective as it utilizes the native $MESI token and avoids mobile platform processing fees.
</Tip>
