---
title: "NFT & Content Management"
description: "Understanding immutable records, ownership rights, and the protocols for content removal."
---

On Mesi, every piece of content uploaded is minted as a **Non-Fungible Token (NFT)**. This blockchain integration ensures that every asset is tradable, every owner is verifiable, and every interaction is recorded in an immutable ledger.

<Frame caption="The NFT Lifecycle: From Upload to Secondary Market">
  <img src="../.gitbook/assets/NFT content management.png" alt="Content Management Workflow" />
</Frame>

## Immutable Content IDs
Every asset is assigned a **Unique Identifier (UID)** that is stored permanently on the blockchain.
* **The Record:** This UID tracks the entire history of the asset—from the initial timestamp of the upload to every subsequent sale or deletion event.
* **The Content:** While the *record* of the action is on-chain (immutable), the *media file* is stored off-chain. This allows creators to maintain "The Right to be Forgotten" by removing the actual media while preserving the integrity of the transaction history.

---

## Content Removal & Ownership

Ownership dictates who has the right to remove content from public view.

| Ownership Status | Removal Rights |
| :--- | :--- |
| **Creator Owned** | You may remove content from your gallery at any time. |
| **User Owned** | Once sold, you cannot remove the content. It remains in the owner's gallery and your portfolio. |

---

## Account Deletion Protocols

Closing a Mesi account involves a structured 48-hour "Cooling-Off" period to protect the financial interests of your NFT holders.

<Steps>
  <Step title="Request Deletion">
    Initiate the process via settings. A **48-hour waiting period** begins.
  </Step>
  <Step title="Owner Notification">
    All users who own your NFTs are notified of the upcoming account deletion.
  </Step>
  <Step title="Refund Window">
    If a user purchased one of your NFTs within 48 hours of your deletion request, they are eligible for a **full refund**, and the NFT is returned to you.
  </Step>
  <Step title="Final Confirmation">
    After 48 hours, you must provide a final confirmation to permanently close the account.
  </Step>
</Steps>

<Warning>
  **Post-Deletion Content:** Upon account closure, any content you still own is deleted. However, content owned by other users is **automatically transferred** to their private galleries to ensure their purchase remains accessible.
</Warning>

---

## AI Personas as NFTs

Beyond standard media, Mesi allows for the minting of **AI Personas** (excluding personal Digital Twins). These are identity-based NFTs that act as a "container" for:
* **Personality Settings:** Behavioral traits and communication styles.
* **Training History:** The data used to refine the AI's responses.
* **Visual Configurations:** Metadata defining the character's appearance.
* **Tradability:** These personas can be owned, licensed, or traded as complete, functioning virtual entities.

---

## Technical Exceptions

To protect the platform's library and other creators, certain assets behave differently upon account deletion:

* **Public Media Library:** Memes, emojis, and sound clips added to the public library are **not removed**. If they were previously paid assets, they transition to "Free Access" for the community.
* **Music & Licensing:** Original music tracks in the open library are removed. However, any user-generated content (UGC) that *incorporated* those tracks will remain active and unaffected.
* **Ad Revenue:** If your sold NFTs were generating ad revenue via a [Revenue Model](/path-to-ads), all future income is transferred to the current NFT owner upon your account deletion.
