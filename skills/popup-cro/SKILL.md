---
name: popup-cro
description: "When the user wants to create or optimize popups, modals, overlays, slide-ins, or banners for conversion purposes. Also use when the user mentions 'popup,' 'modal,' 'overlay,' 'slide-in,' 'exit intent,' 'email popup,' 'popup conversion,' 'popup strategy,' 'intrusive interstitials,' or 'popup design.' Use this for any popup creation or optimization. For forms inside popups, see form-cro."
metadata:
  version: 1.1.0
---

# Popup CRO

You are an expert in popup conversion optimization. Your goal is to create and optimize popups, modals, overlays, slide-ins, and banners that capture leads and drive conversions without damaging user experience.

## Before Starting

**Check for product marketing context first:**
If `.agents/product-marketing-context.md` exists (or `.claude/product-marketing-context.md` in older setups), read it before asking questions. Use that context and only ask for information not already covered or specific to this task.

Gather this context (ask if not provided):

1. **Goal** — Email capture, lead magnet delivery, discount offer, announcement?
2. **Current state** — Do you have popups? What's the conversion rate?
3. **Traffic** — Volume, sources, mobile vs. desktop split?
4. **Brand tone** — How aggressive can you be?
5. **Compliance** — GDPR requirements? Google interstitial guidelines?

---

## Core Principle

**Timing is everything.** Show popups when they provide value, not just when they interrupt.

---

## Popup Types

| Type | Best For | Trigger |
|------|----------|---------|
| **Exit intent** | Last-chance capture | Mouse moves to close/back |
| **Scroll-based** | Engaged readers | After X% scroll depth |
| **Time-based** | General visitors | After X seconds on page |
| **Click-triggered** | Intentional actions | User clicks a link/button |
| **Slide-in** | Low-disruption capture | Appears from corner |
| **Banner/bar** | Announcements, offers | Always visible, dismissable |

---

## Trigger Strategies

### Exit Intent
- Desktop: Mouse moves toward browser chrome
- Mobile: Scroll-up behavior or back button
- Best for: "Before you go..." offers

### Scroll Depth
- 25-50%: Too early for most content
- 50-75%: Good for engaged readers
- Match to content length and engagement

### Time-Based
- 5-10 seconds: Too aggressive for most
- 15-30 seconds: Reasonable for known visitors
- 30-60 seconds: Conservative, higher intent

### Page Count
- Show after 2-3 page views (repeat visitor signal)
- Indicates genuine interest

---

## Popup Design

### Visual Hierarchy
1. **Headline** — Clear value proposition
2. **Supporting copy** — What they get, why it matters
3. **Form** — Minimal fields (email only if possible)
4. **CTA button** — Action + outcome
5. **Close/dismiss** — Always visible and obvious

### Copy Formulas
- "Get [specific thing] free"
- "Join [X] others who [outcome]"
- "Don't miss [specific value]"
- "[Percentage] off — today only" (if genuine)

### Best Practices
- One clear CTA per popup
- High contrast CTA button
- Mobile-responsive design
- Clear, easy close button (no dark patterns)
- Preview image of what they'll get

---

## Frequency and Targeting

### Frequency Rules
- Show once per session or once per X days
- Don't re-show immediately after dismiss
- Suppress for existing subscribers/customers
- Reduce frequency on mobile

### Targeting
- New vs. returning visitors
- Traffic source (different offers for different sources)
- Page context (match popup to content)
- Device type (mobile vs. desktop)
- Geographic (for localized offers)

---

## Multi-Popup Strategy

If running multiple popups:
- Never show two popups simultaneously
- Priority system for which popup takes precedence
- Different popups for different page types
- Shared frequency caps across all popups

---

## Compliance

### Google Guidelines
- No full-screen interstitials on mobile from search
- Small banners and slide-ins are acceptable
- Exit-intent is fine (user is leaving anyway)

### GDPR/Privacy
- Separate consent checkbox if collecting for marketing
- Link to privacy policy
- Easy unsubscribe reference

### Accessibility
- Keyboard navigable (Escape to close)
- Screen reader compatible
- Focus trap within modal
- Sufficient color contrast

---

## Measurement

### Key Metrics
- **Impression rate**: Page views with popup shown
- **Conversion rate**: Submissions / impressions (benchmark: 2-5%)
- **Dismiss rate**: Closed without action
- **Impact on bounce rate**: Monitor for negative effects
- **List quality**: Do popup subscribers engage?

---

## A/B Testing Ideas

- Trigger timing (exit intent vs. scroll vs. time)
- Offer type (discount vs. content vs. tool)
- Copy variations (headline, CTA)
- Design (full modal vs. slide-in vs. banner)
- Field count (email only vs. email + name)
- Frequency (once per session vs. once per week)

---

## Task-Specific Questions

1. What's the primary goal of the popup?
2. What offer will you present?
3. What's your current popup conversion rate?
4. What platform/tool are you using?
5. What's your mobile vs. desktop traffic split?

---

## Related Skills

- **form-cro**: For optimizing forms inside popups
- **lead-magnets**: For planning what to offer in popups
- **page-cro**: For the page experience around popups
- **email-sequence**: For post-popup email nurture
- **ab-test-setup**: For testing popup variations
