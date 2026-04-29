---
title: "A Practical Guide to Writing Better Prompts"
date: 2026-04-29
description: "Most people are one better prompt away from getting what they actually wanted. Here's the simple framework that makes the difference."
tags: ["AI", "Productivity"]
---

![A Practical Guide to Writing Better Prompts](./cover.png)

*Most people are one better prompt away from getting what they actually wanted. Here's the simple framework that makes the difference.*

Most people use AI the same way they use Google — short, vague queries, then frustration when the output misses the mark.

That's not really the model's fault. It's working with what it's given.

The shift that actually helps: stop treating it like a search engine and start treating it like a smart person you're briefing. Give it context, a clear ask, and some guardrails. Not always. Not perfectly. But enough to point it in the right direction.

Here's the framework I use.

## Three things every good prompt answers

**Context** — What's the situation? Who are you, what are you working on, why does it matter?

**Task** — What specifically do you want done?

**Constraints** — How should it look? What should it avoid?

You don't need all three every time. But each one you add narrows the gap between what you meant and what you get.

## A template (use what applies, skip what doesn't)

```
Context: [who you are, what you're working on]
Task: [what you want done]
Input: [paste your text, data, or code here]
Output: [format, length, structure]
Tone: [formal, casual, technical, simple]
Constraints: [what to include or avoid]
```

That's it. Six lines. Most prompts only need three or four of them.

## What this looks like in practice

**Student writing an essay:**

```
I'm an undergrad writing a 1200-word history essay on the causes of WWII.
Write a structured draft with an introduction, three body paragraphs, and a conclusion.
Academic tone, college level, no jargon.
```

**Analyst working in Excel:**

```
I'm reviewing monthly sales data across 12 regions.
Identify trends, flag anomalies, and suggest what might explain the patterns.
Bullet points, keep it concise, focus on business-level insights.
```

**Developer debugging code:**

```
Here's a Python function that's supposed to return sorted results but isn't.
Find the bug, fix it, and explain what was wrong in 2-3 sentences.
[paste code]
```

**Designer presenting to a client:**

```
Create a 10-slide outline for a digital marketing strategy presentation.
Professional tone, persuasive framing, with a clear heading and 3 key points per slide.
```

Notice none of these are perfect. They're just specific enough.

## The part most people skip: iteration

Your first prompt is a starting point, not a final answer. The model gives you something, and you push back:

```
"Make it more concise"
"The tone is too formal, loosen it up"
"Expand on the second point"
"Focus only on the performance angle"
```

This is where the quality actually improves. One well-iterated prompt will beat ten vague ones every time.

## What actually goes wrong

The most common issue isn't bad prompts — it's no structure at all. When you give vague inputs, you get vague outputs, and then you assume the tool isn't that useful. It usually is. It just needed more to work with.

The second issue is stopping at the first response. Treat it like a draft, not a deliverable.

## One more thing: models are not all the same

AI is moving fast. The model you used six months ago behaves differently from the one you're using today — and GPT-5.5 behaves differently from Claude Opus or Sonnet, which behaves differently from Gemini. Same prompt, different outputs. That's just the reality.

The best thing you can do is pick one model and stick with it long enough to develop a feel for it. You start noticing patterns — how it handles ambiguity, where it tends to over-explain, when it needs more structure vs. when it works fine with loose input. That intuition is genuinely useful, and it doesn't transfer perfectly across models.

Most major labs publish prompt guides. Anthropic has one. OpenAI has one. They're worth skimming — they tell you what the model responds well to. But don't treat them as gospel. They're starting points, not rules.

The real way to get good at this is to experiment. Try the same prompt three different ways. See what changes. Break things intentionally. It's okay to burn some tokens figuring out how a model generates — that's not wasted time, it's how you build taste. The people who get the most out of these tools aren't the ones who read the most guides. They're the ones who spent the most time just playing around.

## The honest bottom line

You don't need to be a "prompt engineer." You just need a clear ask, a bit of context, and the willingness to refine it once or twice. That alone gets you most of the way there.
