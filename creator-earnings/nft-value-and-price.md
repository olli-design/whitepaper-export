---
title: "NFT Value & Pricing"
description: "Understanding the distinction between algorithmic valuation and market-driven pricing."
---

On Mesi, every NFT is assigned two distinct financial attributes: **Value** and **Price**. 

While most platforms only show the seller's asking price, Mesi calculates a "Real Value" to provide transparency, prevent market manipulation, and help buyers make informed decisions.

<Frame caption="The NFT Financial Interface: Comparing Value vs. Price">
  <img src="../.gitbook/assets/NFT Value A2 (1).png" alt="Value and Price Metrics" />
</Frame>

---

## Valuation Metrics

Mesi uses an algorithmic approach to determine the intrinsic worth of an asset. These metrics are refreshed daily.

<CardGroup cols={2}>
  <Card title="NFT Value" icon="chart-line">
    The calculated worth of an individual asset. It is based on:
    * **Engagement Score:** Viral reach and interaction rates.
    * **Earnings Potential:** Projected future revenue from ads/PPV.
    * **Historical Data:** Average trade prices and frequency.
    * **Trust Pledge:** The size of the attached [Trust Pledge](/path-to-pledges).
  </Card>
  <Card title="Gallery Value" icon="shop">
    An informational metric representing the creator's total ecosystem health:
    * Sum of all NFT Values (Sold & Unsold).
    * Subscription revenue, weighted by the subscribers' [Engagement Scores](/path-to-engagement).
  </Card>
</CardGroup>

---

## Revenue Attribution Percentage

This metric shows exactly how much of a gallery's total success is driven by a specific NFT. It is calculated by combining direct revenue and a "Pro-Rata" share of subscriptions.

$$\text{Attribution \%} = \frac{\text{Direct NFT Earnings} + (\text{Total Subscription Revenue} / \text{Total NFTs})}{\text{Total Gallery Revenue}}$$

> **Example:**
> A gallery has 10 NFTs and earned $5,000 in subscriptions.
> * One "Star" NFT earned $100 in direct tips/PPV.
> * Its attribution is: **($500 + $100) / $5,100 = 11.7%**.
> * The other 9 NFTs receive a baseline share of **9.8% each**.

---

## The Pricing System

While "Value" is algorithmic, "Price" is the actual amount a buyer pays. Mesi supports three transaction types:
1. **Buy Now:** A fixed price set by the owner.
2. **Auction:** Time-limited bidding.
3. **Private Bid:** Direct offers sent to owners of NFTs marked "Open for Bids."

### Maximum Price Formula
To maintain market stability, the platform enforces a price ceiling based on the asset's current value and the seller's **User Tier**.

$$\text{Max Sale Price} = \text{NFT Value} \times [n]$$

* **[n] Variable:** Starts at **0.5** for entry-level tiers and increases as the seller's account tier rises.
* **Purpose:** Prevents "wash trading" and artificial price inflation on low-tier accounts.

<Frame caption="Pricing and Tier-based limits">
  <img src="../.gitbook/assets/NFT Value B.png" alt="Pricing Interface" />
</Frame>

### Handling Excess Funds
If an interaction results in a price higher than the **Max Sale Price** (e.g., a high-intensity auction or a generous private bid):
* **The Seller:** Receives the amount up to their current Max Price limit.
* **The Escrow:** The surplus funds are held in a secure Mesi Escrow.
* **Unlocking:** These funds are released to the seller as soon as they reach the required **User Tier** to support that price level.

<Tip>
  **Strategic Growth:** To unlock higher prices and access your escrowed funds immediately, consider [Locking $MESI Tokens](/gamification/user-tiers-and-creator-limits) to upgrade your Tier.
</Tip>
