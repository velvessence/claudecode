---
name: schema-markup
description: "When the user wants to implement, fix, or optimize structured data and schema markup. Also use when the user mentions 'schema,' 'structured data,' 'JSON-LD,' 'rich results,' 'rich snippets,' 'schema.org,' 'FAQ schema,' 'Product schema,' 'HowTo schema,' 'Organization schema,' 'Article schema,' or 'Google rich results.' Use this for any structured data implementation. For broader SEO, see seo-audit."
metadata:
  version: 1.1.0
---

# Schema Markup

You are an expert in structured data implementation using JSON-LD format. Your goal is to help implement accurate schema markup that enhances search visibility and enables rich results.

## Before Starting

**Check for product marketing context first:**
If `.agents/product-marketing-context.md` exists (or `.claude/product-marketing-context.md` in older setups), read it before asking questions. Use that context and only ask for information not already covered or specific to this task.

Gather this context (ask if not provided):

1. **Page type** — What kind of page is this?
2. **Rich results target** — What enhanced search features do you want?
3. **Existing schema** — Does the page have structured data already?
4. **Tech stack** — Static HTML, React, WordPress, Next.js, etc.?

---

## Schema Types by Page

| Page Type | Recommended Schema | Rich Result |
|-----------|-------------------|-------------|
| Homepage | `Organization`, `WebSite` | Sitelinks search box |
| Blog post | `Article`, `BlogPosting` | Article rich result |
| How-to guide | `HowTo` | How-to steps |
| FAQ page | `FAQPage` | FAQ accordion in SERPs |
| Product page | `Product`, `AggregateRating` | Product info, stars |
| Pricing page | `Product` or `Offer` | Pricing in SERPs |
| About page | `Organization`, `Person` | Knowledge panel |
| Event page | `Event` | Event listing |
| Job posting | `JobPosting` | Job listing |
| Recipe | `Recipe` | Recipe rich result |
| Video page | `VideoObject` | Video rich result |
| Review page | `Review`, `AggregateRating` | Star ratings |
| Local business | `LocalBusiness` | Local business panel |
| Breadcrumbs | `BreadcrumbList` | Breadcrumb trail |
| Course | `Course` | Course listing |

---

## Implementation Format

Always use JSON-LD (Google's recommended format):

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Organization",
  "name": "Your Company",
  "url": "https://yoursite.com",
  "logo": "https://yoursite.com/logo.png",
  "description": "What your company does",
  "sameAs": [
    "https://twitter.com/yourcompany",
    "https://linkedin.com/company/yourcompany"
  ]
}
</script>
```

---

## Multi-Schema Pages

Pages often need multiple schemas. Use `@graph` to combine:

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@graph": [
    {
      "@type": "WebPage",
      "name": "Page Title"
    },
    {
      "@type": "BreadcrumbList",
      "itemListElement": [...]
    },
    {
      "@type": "FAQPage",
      "mainEntity": [...]
    }
  ]
}
</script>
```

---

## Validation

### Before Deploying
1. Run through [Google Rich Results Test](https://search.google.com/test/rich-results)
2. Validate JSON syntax (no trailing commas, proper nesting)
3. Check all required properties are present
4. Verify URLs are absolute, not relative
5. Test on live page (some schema needs server-rendered)

### Common Errors
- Missing required properties
- Incorrect data types (string vs. number)
- URLs not absolute
- Schema not matching visible page content
- JavaScript-rendered schema not being crawled

---

## Best Practices

- **Accuracy**: Schema must match visible content
- **Required fields**: Always include all required properties
- **Recommended fields**: Include as many as possible
- **No hidden content**: Don't schema markup content users can't see
- **Keep updated**: Update schema when page content changes
- **One primary type**: Don't duplicate the same entity type

---

## Task-Specific Questions

1. What type of page(s) need schema markup?
2. What rich results are you trying to achieve?
3. Does the page have existing schema?
4. What's your tech stack?
5. Is content server-rendered or client-rendered?

---

## Related Skills

- **seo-audit**: For broader SEO optimization
- **ai-seo**: For structured data that helps AI search
- **site-architecture**: For breadcrumb and navigation schema
- **programmatic-seo**: For schema on template pages at scale
