---
title: "Mesi FeelFlow System"
description: "An AI-driven emotional discovery engine that guides your content experience based on your mood."
---

The **FeelFlow System** is Mesi's proprietary content delivery engine. Unlike traditional algorithms that only prioritize engagement, FeelFlow allows you to select your **current mood** and a **target mood**, guiding you through an emotional journey with curated content.

<div className="flex gap-4">
  <img src="../.gitbook/assets/The Buzz - content new with hive.png" alt="Mood Interface" width="200" />
  <img src="../.gitbook/assets/The Buzz - content mood selector.png" alt="Mood Selector" width="200" />
</div>

## How it Works

The system calculates a "Transition Plan" to move you from your starting point to your desired emotional state.

<Steps>
  <Step title="Current Mood Selection">
    The user manually selects their current feeling or allows the AI to detect it based on interaction patterns.
  </Step>
  <Step title="Target Mood Setting">
    The user picks the mood they wish to reach (e.g., from "Stressed" to "Relaxed").
  </Step>
  <Step title="Content Transition Plan">
    The system selects a sequence of content that aligns with the user's interests while gradually shifting the emotional tone.
  </Step>
  <Step title="Real-Time Adaptation">
    The path adapts instantly based on behavior such as skips, pauses, or replays to ensure the journey remains comfortable.
  </Step>
</Steps>

---

## Emotional Safety & Guardrails

To ensure a positive user experience, Mesi implements psychological guardrails designed by content experts:

* **Smooth Transitions:** The system avoids "emotional whiplash" by preventing sharp changes (e.g., jumping directly from a deeply sad state to a high-energy party state).
* **Context Awareness:** The algorithm considers external factors like the time of day, your current location, and device type to refine the content selection.
* **Opt-Out Control:** FeelFlow can be disabled at any time for a standard, neutral browsing experience.

---

## Mood Discovery Options



<CardGroup cols={3}>
  <Card title="Manual Selection" icon="face-smile">
    Use emoji-based choices to tell the system exactly how you feel and where you want to go.
  </Card>
  <Card title="Inferred Mood" icon="brain">
    Let the AI analyze scroll speed and pause times to detect your mood passively.
  </Card>
  <Card title="Profile Moods" icon="user-gear">
    Tag your profile with "Passive Moods" to shape your long-term content recommendations.
  </Card>
</CardGroup>
