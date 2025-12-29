---
title: "Revenue & Reward Distribution"
description: "Learn how gallery contributions and engagement rewards are calculated and shared across the NFT ecosystem."
---

The Mesi economy is designed to reward long-term value. Through **Revenue Contributions**, creators can share their success with their community, while **Engagement Rewards** incentivize the platform's most active galleries.

## Revenue Contribution

Creators can choose to allocate a percentage of their personal revenue (from sales, tips, or subscriptions) back into their gallery. This revenue is then distributed among all NFTs in that gallery—including those currently owned by fans.

### The 12-Month Moving Average
To prevent market manipulation, Mesi uses a 12-month moving average to calculate your effective contribution rate.

$$Effective\% = \frac{\sum (\text{Monthly Contribution \% over last 12 months})}{12}$$

> **Scenario:**
> If a creator contributes 100% for 6 months and then drops to 50% for the next 5 months, their effective contribution for a sale in the 12th month would be **77%**.
> * On a $1,000 sale, **$770** is distributed to the gallery, and **$230** goes to the creator.

---

## Revenue Distribution to NFTs

Once revenue is allocated to a gallery, it is distributed among individual NFTs based on their [Engagement Rating](/path-to-engagement). 



### Distribution Formula
The share for a specific NFT is determined by its individual performance relative to the rest of the gallery:

$$\text{NFT Revenue Share} = \text{Gallery Contribution} \times \frac{\text{NFT Engagement Rating}}{\sum (\text{Gallery Engagement Ratings})}$$

<Note>
  **The Buyer Exclusion Rule:** To maintain economic fairness, the buyer of an NFT does not receive a share of the specific payment they just made for that asset.
</Note>

### Example: A $1,000 Gallery Distribution
| Asset | Owner | Engagement Rating | Revenue Share |
| :--- | :--- | :--- | :--- |
| **NFT 1** | Creator | 40 | $200 |
| **NFT 5** | Fan A | 50 | $250 |
| **NFT 9** | Fan B | 5 | $25 |

---

## Engagement Rewards ($MESI)

Beyond direct sales, Mesi distributes $MESI tokens from the platform treasury (and eventually from app fees) to incentivize high-quality content.

### The Weekly Reward Cycle
Rewards are calculated weekly and distributed through a two-step process:

<Steps>
  <Step title="Gallery Allocation">
    The total weekly reward pool is split among all galleries based on their share of the platform's total Engagement Score.
  </Step>
  <Step title="NFT Distribution">
    The rewards assigned to a gallery are then divided among its individual NFTs using the same engagement-weighted formula used for revenue.
  </Step>
</Steps>

---

## Visual Architecture

The following diagrams illustrate the flow of capital from both internal (Creator-contributed) and external (Treasury-funded) sources.

<Frame caption="Phase 1: Revenue Contribution Logic">
  <img src="../.gitbook/assets/Revenue contribution 1.png" alt="Revenue Flow" />
</Frame>

<Frame caption="Phase 2: Final Distribution to Owners">
  <img src="../.gitbook/assets/Revenue contribution 2.png" alt="Reward Flow" />
</Frame>

<Tip>
  **For Collectors:** Buying NFTs with high Engagement Ratings in galleries where the creator has a high "Effective Contribution %" is a powerful strategy for earning passive $MESI rewards and revenue shares.
</Tip>
