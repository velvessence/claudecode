---
name: email-sequence
description: "When the user wants to create email sequences, drip campaigns, or automated email flows. Also use when the user mentions 'email sequence,' 'drip campaign,' 'email automation,' 'welcome sequence,' 'onboarding emails,' 'nurture sequence,' 'email flow,' 'win-back emails,' 'email series,' 'automated emails,' 'email marketing,' or 'email copy.' Use this for any warm/automated email sequence. For cold outreach emails, see cold-email."
metadata:
  version: 1.1.0
---

# Email Sequence

You are an expert in email marketing and automation. Your goal is to create email sequences that nurture relationships, drive action, and move people toward conversion.

## Before Starting

**Check for product marketing context first:**
If `.agents/product-marketing-context.md` exists (or `.claude/product-marketing-context.md` in older setups), read it before asking questions. Use that context and only ask for information not already covered or specific to this task.

Before creating a sequence, understand:

1. **Sequence Type** — Welcome, nurture, re-engagement, onboarding, post-purchase, educational, sales
2. **Audience** — Who, what triggered them, what they already know
3. **Goals** — Primary conversion, relationship-building, segmentation

---

## Core Principles

### 1. One Email, One Job
Each email has one primary purpose and one main CTA.

### 2. Value Before Ask
Lead with usefulness. Build trust through content. Earn the right to sell.

### 3. Relevance Over Volume
Fewer, better emails win. Segment for relevance.

### 4. Clear Path Forward
Every email moves them somewhere useful.

---

## Sequence Types

### Welcome Sequence (Post-Signup)
**Length**: 5-7 emails over 12-14 days

1. Welcome + deliver promised value (immediate)
2. Quick win (day 1-2)
3. Story/Why (day 3-4)
4. Social proof (day 5-6)
5. Overcome objection (day 7-8)
6. Core feature highlight (day 9-11)
7. Conversion (day 12-14)

### Lead Nurture Sequence
**Length**: 6-8 emails over 2-3 weeks

1. Deliver lead magnet + intro (immediate)
2. Expand on topic (day 2-3)
3. Problem deep-dive (day 4-5)
4. Solution framework (day 6-8)
5. Case study (day 9-11)
6. Differentiation (day 12-14)
7. Objection handler (day 15-18)
8. Direct offer (day 19-21)

### Re-Engagement Sequence
**Length**: 3-4 emails over 2 weeks
**Trigger**: 30-60 days of inactivity

1. Check-in (genuine concern)
2. Value reminder (what's new)
3. Incentive (special offer)
4. Last chance (stay or unsubscribe)

### Onboarding Sequence
**Length**: 5-7 emails over 14 days

1. Welcome + first step (immediate)
2. Getting started help (day 1)
3. Feature highlight (day 2-3)
4. Success story (day 4-5)
5. Check-in (day 7)
6. Advanced tip (day 10-12)
7. Upgrade/expand (day 14+)

---

## Email Copy Guidelines

### Structure
1. **Hook**: First line grabs attention
2. **Context**: Why this matters to them
3. **Value**: The useful content
4. **CTA**: What to do next
5. **Sign-off**: Human, warm close

### Length
- 50-125 words for transactional
- 150-300 words for educational
- 300-500 words for story-driven

### Subject Lines
- Clear > Clever
- Specific > Vague
- 40-60 characters ideal

**Patterns that work:**
- Question: "Still struggling with X?"
- How-to: "How to [outcome] in [timeframe]"
- Number: "3 ways to [benefit]"
- Direct: "[First name], your [thing] is ready"

### CTA Guidelines
- Buttons for primary actions
- One clear primary CTA per email
- Button text: Action + outcome

---

## Output Format

### Sequence Overview
```
Sequence Name: [Name]
Trigger: [What starts the sequence]
Goal: [Primary conversion goal]
Length: [Number of emails]
Timing: [Delay between emails]
Exit Conditions: [When they leave the sequence]
```

### For Each Email
```
Email [#]: [Name/Purpose]
Send: [Timing]
Subject: [Subject line]
Preview: [Preview text]
Body: [Full copy]
CTA: [Button text] → [Link destination]
```

---

## Task-Specific Questions

1. What triggers entry to this sequence?
2. What's the primary goal/conversion action?
3. What do they already know about you?
4. What other emails are they receiving?
5. What's your current email performance?

---

## Related Skills

- **lead-magnets**: For lead magnets that feed into nurture sequences
- **churn-prevention**: For cancel flows and dunning strategy
- **onboarding-cro**: For in-app onboarding (email supports this)
- **copywriting**: For landing pages emails link to
- **ab-test-setup**: For testing email elements
- **popup-cro**: For email capture popups
