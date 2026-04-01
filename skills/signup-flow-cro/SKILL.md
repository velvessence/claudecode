---
name: signup-flow-cro
description: "When the user wants to optimize their signup or registration flow. Also use when the user mentions 'signup flow,' 'registration flow,' 'signup form,' 'signup conversion,' 'registration optimization,' 'signup completion rate,' 'signup friction,' 'signup drop-off,' 'account creation,' or 'users aren't signing up.' Use this for signup/registration optimization. For post-signup onboarding, see onboarding-cro. For non-signup forms, see form-cro."
metadata:
  version: 1.1.0
---

# Signup Flow CRO

You are an expert in optimizing signup and registration flows. Your goal is to reduce friction, increase completion rates, and set users up for successful activation.

## Before Starting

**Check for product marketing context first:**
If `.agents/product-marketing-context.md` exists (or `.claude/product-marketing-context.md` in older setups), read it before asking questions. Use that context and only ask for information not already covered or specific to this task.

Before providing recommendations, understand:

1. **Flow Type** — Free trial, freemium, paid, waitlist, B2B vs B2C
2. **Current State** — Steps/screens, required fields, completion rate, drop-off points
3. **Constraints** — What data is genuinely needed? Compliance requirements?

---

## Core Principles

### 1. Minimize Required Fields
Every field reduces conversion. For each field ask: Do we need this before they can use the product?

**Priority:**
- Essential: Email, Password
- Often needed: Name
- Usually deferrable: Company, Role, Team size, Phone

### 2. Show Value Before Commitment
Can they experience the product before creating an account?

### 3. Reduce Perceived Effort
Progress indicators, smart defaults, pre-fill when possible.

### 4. Remove Uncertainty
Clear expectations, no surprises, show what happens after signup.

---

## Field Optimization

### Email
- Single field (no confirmation)
- Inline validation, typo detection

### Password
- Show/hide toggle
- Requirements shown upfront, not after failure
- Allow paste, show strength meter

### Name
- Single "Full name" vs. First/Last (test this)
- Only require if immediately used

### Social Auth
- Place prominently (often higher conversion)
- B2C: Google, Apple, Facebook
- B2B: Google, Microsoft, SSO

---

## Single-Step vs. Multi-Step

### Single-Step: When
- 3 or fewer fields
- Simple B2C products
- High-intent visitors

### Multi-Step: When
- More than 3-4 fields needed
- Complex B2B products
- Need different info types

### Multi-Step Best Practices
- Progress indicator
- Easy questions first
- Allow back navigation
- Save progress
- Each step feels fast

---

## Trust & Friction Reduction

- "No credit card required" (if true)
- "Free forever" or trial length
- Privacy note
- Security badges
- Testimonial near form
- Specific error messages
- Don't clear form on error

---

## Mobile Optimization

- 44px+ touch targets
- Appropriate keyboard types
- Autofill support
- Single column
- Sticky CTA button

---

## Common Signup Patterns

### B2B SaaS Trial
1. Email + Password (or Google auth)
2. Name + Company
3. → Onboarding flow

### B2C App
1. Google/Apple auth OR Email
2. → Product experience
3. Profile completion later

### Waitlist
1. Email only
2. Optional use case question
3. → Confirmation

---

## Measurement

### Key Metrics
- Form start rate (landed → started)
- Form completion rate (started → submitted)
- Field-level drop-off
- Social auth vs. email ratio
- Mobile vs. desktop completion

---

## Task-Specific Questions

1. What's your current signup completion rate?
2. Do you have field-level drop-off data?
3. What data is absolutely required before product use?
4. Are there compliance requirements?
5. What happens immediately after signup?

---

## Related Skills

- **onboarding-cro**: For post-signup optimization
- **form-cro**: For non-signup forms
- **page-cro**: For the landing page leading to signup
- **ab-test-setup**: For testing signup flow changes
