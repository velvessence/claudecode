---
name: product-marketing-context
description: "When the user wants to create or update their product marketing context document. Also use when the user mentions 'product marketing context,' 'positioning document,' 'messaging document,' 'brand foundation,' 'marketing brief,' 'product positioning,' 'set up marketing context,' or when another skill references the product-marketing-context.md file and it doesn't exist yet."
metadata:
  version: 1.1.0
---

# Product Marketing Context

You help build and maintain a foundational marketing document (`.agents/product-marketing-context.md`) that captures product positioning, audience, and messaging. This document prevents repeating the same information across every marketing task.

## How It Works

### First Time Setup

Check if `.agents/product-marketing-context.md` exists. If not, offer two paths:

**Option A: Auto-Draft from Codebase (Recommended)**
Scan README, landing pages, marketing materials, and code to create a V1 draft. Then refine with the user.

**Option B: Start from Scratch**
Walk through each section conversationally, one at a time.

### Updates
When the document exists, review it and ask what's changed. Update specific sections.

---

## Document Sections

Build the document with these 12 sections:

### 1. Product Overview
- What does the product do? (One paragraph)
- What category does it belong to?
- Key capabilities (not a feature list — capabilities)

### 2. Target Audience
- Who is this for? (Company type, size, industry)
- Who is this NOT for?

### 3. Personas
- 1-3 primary personas
- Role, goals, daily challenges
- How they discover and evaluate tools

### 4. Pain Points
- What problems does the product solve?
- What are customers doing today without it?
- Use verbatim customer language when possible

### 5. Competitive Landscape
- Top 3-5 competitors
- How you're different
- Where competitors are better (be honest)

### 6. Differentiation
- What's genuinely unique?
- Why should someone choose you over alternatives?

### 7. Common Objections
- What makes people hesitate to buy?
- How do you address each objection?

### 8. Switching Dynamics
- What are people switching from?
- What makes switching hard?
- What makes switching easy?

### 9. Customer Language
- **Exact phrases** customers use to describe their problems
- **Exact phrases** customers use to describe the solution
- This is the most valuable section — verbatim quotes over polished descriptions

### 10. Brand Voice
- Tone descriptors (professional but warm, direct but empathetic, etc.)
- Words/phrases to use
- Words/phrases to avoid

### 11. Proof Points
- Key metrics (customer count, growth, performance stats)
- Notable customers or logos
- Case study highlights

### 12. Goals
- Current marketing priorities
- Key metrics being targeted
- Upcoming launches or initiatives

---

## Core Philosophy

**Exact customer phrases are more valuable than refined descriptions.** Customer language reflects actual thinking and is more effective in copy, ads, and content than polished marketing speak.

---

## Output Format

Generate a complete `.agents/product-marketing-context.md` file with all 12 sections. Mark any sections that need more information with `<!-- NEEDS INPUT -->` comments.

---

## Task-Specific Questions

1. Do you have existing positioning or messaging documents?
2. Do you have access to customer interviews, surveys, or reviews?
3. What's your biggest marketing challenge right now?
4. Is there a specific section you want to focus on first?

---

## Related Skills

All other marketing skills reference this document. Build it first for best results across:
- **copywriting**, **content-strategy**, **email-sequence**, **paid-ads**, **page-cro**, and all others
