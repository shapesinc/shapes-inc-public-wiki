---
description: Welcome to the control center of your Shape—the AI Engine.
---

# AI Engine

The AI Engine tab is just as important as the Personality tab, and it holds the key to defining how your shape interacts with users. Here, you can configure your shape's language, conversational style, AI model, creativity, memory usage, knowledge accuracy, and more. Let’s break it down step-by-step:

***

### **Preset**

Presets determine how your shape interacts with users. They are the foundation of your shape’s conversational behavior.

1.  **Language Section**\
    Choose the language your shape will use for communication. The default language is English.\


    <figure><img src="../../../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>
2.  **Engine Preset**\
    This is the most crucial part of tailoring your shape’s interactions. It allows you to specify a conversation style or interaction traits.\


    * To learn more about writing your own preset, [check this out](https://wiki.shapes.inc/shape-essentials/advanced-customization/ai-engine/presets).



    <figure><img src="../../../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>

***

### **Generation**

Select the AI model (LLM) your shape will use for communication.

* [Learn more about AI models](ai-engine-models.md)

***

### **Advanced Generation**

This section manages how your shape generates responses.\


<figure><img src="../../../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
**Warning:** If you’re a beginner, **DO NOT MODIFY** settings here unless you’re confident about what you’re doing.
{% endhint %}

***

### **Time**

Assign a timezone to your shape and decide whether it should be aware of the current time in its responses.\


<figure><img src="../../../.gitbook/assets/image (3) (1).png" alt=""><figcaption></figcaption></figure>

***

### **Short-Term Memory (STM)**

STM determines the number of recent messages your shape considers when generating a reply.

* **Purpose:** Keeps your shape updated on the context of the ongoing conversation.
*   **Default and suggested value:** 15 messages.\


    <figure><img src="../../../.gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure>

***

### **Long-Term Memory (LTM)**

LTM allows your shape to reference past interactions or roleplays when generating replies.

1. **Number of Memories**
   * Sets how many past memories your shape can reference.
   * Suggested value: 1 (to prevent confusion).
   * Disabling LTM keeps roleplays fresh, ensuring responses don’t rely on past interactions.
2. **Memory Similarity Threshold**
   * Controls how closely related a memory must be to the current context for it to be referenced.
   * Suggested value: **0.3** (lower values yield higher accuracy).
3.  **Frequency**

    * Shapes generate memories automatically, viewable in the **Memory** tab.

    <div data-full-width="true"><figure><img src="../../../.gitbook/assets/image (5) (1).png" alt=""><figcaption></figcaption></figure></div>
4.  **Privacy Settings**\
    Decide how private your shape’s conversations and memories should be.

    **Privacy Levels:**

    * **Private:** DMs and server memories are isolated.
    * **Shared:** Memory is shared within the same server.
    * **Global:** Memories from DMs and servers are not isolated.

***

### **Knowledge**

This section manages how accurately your shape uses information stored in the **Knowledge** tab.

* **Threshold:** Lower values yield higher accuracy.
*   **Preferred value:** **0.3.**\


    <figure><img src="../../../.gitbook/assets/image (6) (1).png" alt=""><figcaption></figcaption></figure>

***

With these settings, you should be able to configure your shape effortlessly! If you run into issues, don’t hesitate to reach out to us—[**you know where to find us**!](https://discord.gg/shapes)
