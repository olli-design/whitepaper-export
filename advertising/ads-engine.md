---
title: "Ads Engine"
description: "Configure automated revenue streams for your content and profile using the Mesi Ad Engine."
---

The Mesi Ads Engine functions similarly to Google AdSense, allowing creators to monetize their attention and traffic. By embedding ad-serving rules directly into their NFTs, creators can generate recurring income through three primary ad placements.

<Frame caption="Mesi Ad Engine Dashboard">
  <img src="../.gitbook/assets/Ad Engine.png" alt="Ad Engine Overview" />
</Frame>

## Ad Placement Types

<CardGroup cols={3}>
  <Card title="Content Ads" icon="image">
    Displayed immediately when a user opens a specific piece of content (static or video).
  </Card>
  <Card title="Gallery Ads" icon="grid-2">
    Displayed when a user visits a creator's main profile or specific collection gallery.
  </Card>
  <Card title="In-Content Ads" icon="play">
    Audio or video mid-rolls that play during consumption (available for Music and Podcasts).
  </Card>
</CardGroup>

---

## Ad Parametrization

Creators have granular control over the "ad load" their fans experience. These settings are immutable once the NFT is sold.

### Frequency Settings
You can set the ratio of views to ads displayed:
* **1:1 Ratio:** An ad shows every time the content is accessed.
* **1:5 Ratio:** An ad shows only once every five views.
* **Aggressive (2:1):** Two ads are shown for every single view.

### In-Content Controls
For audio and video, you can further refine the experience:
* **Max Length:** Limit the duration of a single ad (e.g., max 15 seconds).
* **Max Count:** The total number of ads allowed per piece of content.
* **Min Distance:** The minimum time gap required between two ad breaks.

<Warning>
  **The 15% Rule:** To preserve high-quality user experience, the total duration of ads (**Max Length x Max Count**) cannot exceed **15%** of the total content length.
</Warning>

---

## Revenue Models

When minting an NFT, the creator defines who receives the ad revenue. This policy is built into the NFT's smart contract.

| Model | Revenue Recipient | Impact on NFT Value |
| :--- | :--- | :--- |
| **Royalty** | **Creator** always receives 100% of revenue. | Neutral; the NFT is valued purely on its content/perks. |
| **Ownership** | **Current NFT Owner** receives 100% of revenue. | High; the NFT becomes a yield-bearing asset. |
| **Hybrid** | Revenue is **split** between Creator and Owner. | Balanced; provides long-term creator royalties and owner incentives. |

---

## Strategy & Best Practices

Finding the balance between immediate profit and long-term asset value is key to success on Mesi.

<CardGroup cols={2}>
  <Card title="The Overloaded Approach" icon="circle-exclamation">
    **Example:** A creator runs ads every 10 seconds.
    * **Result:** High short-term revenue, but massive drop in engagement.
    * **Impact:** NFT value plummets because no one wants to watch the content.
  </Card>
  <Card title="The Balanced Approach" icon="scale-balanced">
    **Example:** A creator shows one ad every 5 views (2% of total time).
    * **Result:** High engagement and consistent traffic.
    * **Impact:** NFT value increases significantly as a reliable, passive income asset for owners.
  </Card>
</CardGroup>

<Note>
  Ad settings can only be modified while the original creator owns the NFT. Once sold, these settings remain locked unless the creator repurchases the NFT.
</Note>
