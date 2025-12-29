---
title: "Challenges"
description: "Launch purpose-driven micro-fundraisers with escrow-backed accountability and dynamic fan interactions."
---

**Challenges** are Mesi’s evolution of crowdfunding. Instead of rigid, long-term campaigns, Challenges are spontaneous, interactive "Dares" where creators commit to a specific action once a funding target is met.

<div className="flex gap-4">
  <img src="../.gitbook/assets/Challenge fixed.png" alt="Challenge Setup" width="200" />
  <img src="../.gitbook/assets/Challenge 2.png" alt="Challenge Active" width="200" />
</div>

## How It Works

A Challenge is built on a simple "If X, then Y" logic. Creators set a goal, a deadline, and a promise.



<Steps>
  <Step title="Launch">
    Define your goal (e.g., "1,000 USDC") and your commitment (e.g., "I will record a new song by Feb 1st"). 
  </Step>
  <Step title="Fundraising">
    Fans contribute "Bid-Tips" toward the goal. These funds are held securely in escrow by the platform.
  </Step>
  <Step title="Threshold Check">
    If the target is reached within the timeframe (max 7 days), the creator moves to the execution phase.
  </Step>
  <Step title="Verification">
    Once the task is done, the creator marks it as "Completed," triggering a 24-hour dispute window for transparency.
  </Step>
</Steps>

---

## Possible Outcomes

To ensure fairness, Mesi uses automated smart contract logic to handle the funds based on the following three scenarios:

<CardGroup cols={3}>
  <Card title="Successful Delivery" icon="check-double">
    Creator finishes the task and clicks "Completed." After a 24-hour dispute window, funds are released to the creator.
  </Card>
  <Card title="Target Met, No Action" icon="clock-rotate-left">
    If the creator fails to mark the challenge as completed within the defined window, all funds are **automatically refunded** to fans.
  </Card>
  <Card title="Target Not Met" icon="user-slash">
    The creator can choose to deliver anyway (receiving partial funds) or reject the challenge, triggering immediate refunds.
  </Card>
</CardGroup>

---

## Fees & Incentives

Mesi encourages the use of the native ecosystem through a tiered fee structure:

| Funding Currency | Platform Commission |
| :--- | :--- |
| **USDC** | 10% |
| **$MESI Tokens** | 5% (Incentivized Rate) |

### Engagement Rewards
Participating in a successfully completed challenge grants **Engagement Score** bonuses to fans. 
* *Note: Refused or expired challenges do not trigger bonuses to prevent system abuse.*

---

## Limits & Safeguards

<Warning>
  **Time Sensitive:** Each challenge can run for a maximum of **7 days**. The completion window after reaching the goal cannot exceed **30 days**.
</Warning>

* **Goal Caps:** Your maximum fundraising goal is determined by your [Account Tier](/gamification/user-tiers-and-creator-limits).
* **Minimum Contribution:** $1 (in either USDC or $MESI).
* **Dispute Resolution:** If a fan files a valid complaint during the 24-hour window, Mesi moderators manually review the content before any funds are released.
