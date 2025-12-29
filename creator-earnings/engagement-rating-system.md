---
title: "Engagement Rating System"
description: "Understanding how Mesi calculates and weights user activity to drive fair revenue distribution."
---

The **Engagement Rating System** is a backend framework that measures the value and impact of activity across the Mesi platform. Unlike traditional platforms where every "view" is equal, Mesi weights engagement based on the quality of the user, ensuring that **fair rewards and revenue distribution** flow to the most impactful galleries and NFTs.

<Note>
  **System Independence:** While Engagement Ratings influence [Valuation Mechanics](/path-to-valuation), they are independent backend metrics and are not publicly visible to users.
</Note>

## How Engagement is Measured

Every 24 hours, the system audits measurable behaviors to assign points. Key variables include:

* **Attention:** Total time spent viewing specific content.
* **Active Interaction:** Likes, shares, comments, and direct responses.
* **Economic Support:** Purchases, tips, and bidding activity.
* **Influence Power:** Points received via delegation or community contribution.

---

## The Three-Tier Scoring Model

Mesi utilizes a hierarchical scoring model where user quality directly impacts the success of the content they consume.

### 1. User Score
The foundation of the system. It distinguishes between passive "scrollers" and high-value ecosystem participants.

* **High-Value Users:** Hold valuable NFTs, stake or lock $MESI tokens, and contribute meaningfully to the community.
* **Low-Value Users:** Occasional viewers with minimal platform investment.

> **Example:** > **John** (High-Value) receives **200 points** based on his staking and spending history.  
> **Paul** (Low-Value) receives **5 points** due to minimal interaction and zero token holdings.

### 2. NFT Score
Measures the activity an individual NFT attracts, **weighted** by the User Scores of the fans interacting with it.

<div className="flex gap-4">
  <img src="../.gitbook/assets/NFT performance.png" alt="NFT Stats" width="200" />
  <img src="../.gitbook/assets/Your NFT performance.png" alt="Performance Detail" width="200" />
</div>

**Calculation Example:** If John (200 pts) views an NFT for 2 minutes and Paul (5 pts) views it for 20 minutes:
* John’s contribution: $2 \text{ mins} \times 200 = 400 \text{ points}$
* Paul’s contribution: $20 \text{ mins} \times 5 = 100 \text{ points}$
* **Total NFT Score: 500 points**

### 3. Gallery Score
The aggregate score of a creator's entire presence, combining specific NFT performance with general profile engagement.

<div className="flex gap-4">
  <img src="../.gitbook/assets/Gallery performance.png" alt="Gallery Overview" width="200" />
  <img src="../.gitbook/assets/Gallery statistics.png" alt="Gallery Analytics" width="200" />
</div>

**Gallery Score components:**
* **Sum of NFT Scores:** The total points earned by every individual NFT in the gallery.
* **General Activity:** Time spent on the creator's bio, profile, and navigation, weighted by User Scores.

---

## Visual Summary

The following chart illustrates the flow of engagement points from individual users to the broader gallery ecosystem.

<Frame caption="The Mesi Engagement Rating Architecture">
  <img src="../.gitbook/assets/Engagement rating system.png" alt="Engagement Rating Mechanics" />
</Frame>

<Tip>
  **Creator Strategy:** To maximize your revenue, focus on attracting high-value users (Stakers and Collectors) rather than just high-volume traffic. A single interaction from a "Whale" can be worth 40x more than a standard view.
</Tip>
