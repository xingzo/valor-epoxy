# SEO Action Plan — www.valorepoxy.com

**Generated:** March 2, 2026
**Current Score:** 41/100
**Target Score:** 70+ / 100

---

## Critical — Fix Immediately

These issues are actively harming search visibility and should be resolved this week.

### 1. Rename Page URL Slugs
**Impact:** High | **Effort:** Low | **Category:** Technical SEO

The site uses meaningless URL slugs that provide zero keyword value.

| Current | Change To |
|---------|-----------|
| `/blank-1` | `/about` |
| `/blank-2` | `/get-a-quote` |
| `/blank-3` | `/services` or `/epoxy-flooring-services` |
| `/blank-4` | `/contact` |

**How:** In Wix Editor → Pages menu → click the three dots next to each page → "Rename" or "SEO (Google)" → update the URL slug. Set up 301 redirects from old URLs to new ones (Wix does this automatically when you change slugs via the SEO settings).

### 2. Rename Portfolio Project URLs
**Impact:** High | **Effort:** Low | **Category:** Technical SEO

| Current | Change To (example) |
|---------|---------------------|
| `/project-title-1` | `/residential-garage-epoxy-dallas` |
| `/project-title-2` | `/commercial-warehouse-coating-fort-worth` |
| `/project-title-3` | `/metallic-epoxy-floor-dfw` |
| etc. | (descriptive names based on actual projects) |

**How:** In Wix Editor → Portfolio → click each project → Settings → update the URL slug.

### 3. Add H1 to Homepage
**Impact:** High | **Effort:** Low | **Category:** On-Page SEO

The homepage has no H1 tag. Add one that includes the primary keyword and location:

**Suggested H1:** "Dallas-Fort Worth Epoxy Flooring & Concrete Coatings"

**How:** In Wix Editor, add a text element to the hero section and set it to "Heading 1" in the text formatting toolbar.

### 4. Add og:image and twitter:image
**Impact:** Medium | **Effort:** Low | **Category:** On-Page SEO

When the site is shared on social media, no preview image appears. Add a high-quality image (1200x630px recommended) showing your best epoxy flooring work.

**How:** In Wix → Marketing & SEO → SEO Tools → Social Share Preview → upload a custom image for each page.

---

## High — Fix Within 1 Week

These significantly impact rankings and should be addressed promptly.

### 5. Expand LocalBusiness Schema
**Impact:** High | **Effort:** Medium | **Category:** Schema

The current LocalBusiness schema is missing critical fields. Add:

- `description`: "Professional epoxy flooring, concrete coatings, and polishing services in Dallas-Fort Worth, TX"
- `areaServed`: Dallas-Fort Worth metropolitan area (list specific cities)
- `priceRange`: e.g., "$$" or "$500-$10,000"
- `openingHoursSpecification`: Business hours
- `geo`: Latitude/longitude of your primary service area
- `sameAs`: Links to Instagram, Facebook, TikTok profiles
- `telephone`: Format as `+1-972-322-8643`
- `addressLocality`: "Dallas" or "Fort Worth"

**How:** Wix → Marketing & SEO → SEO Tools → Structured Data Markup → edit the LocalBusiness block.

### 6. Rewrite Services Page Content
**Impact:** High | **Effort:** Medium | **Category:** Content

The current services page uses generic template text ("We have the experience and skills necessary..."). Replace with:

- Unique descriptions for each service with specific details
- Include keywords naturally (epoxy flooring, concrete coating, polished concrete, garage floor, DFW)
- Add pricing ranges or "starting from" estimates
- Mention specific materials and brands used
- Describe the installation process for each service
- Include estimated timelines
- Target word count: 300-500 words per service

### 7. Trim Meta Descriptions to 155-160 Characters
**Impact:** Medium | **Effort:** Low | **Category:** On-Page SEO

Four pages have meta descriptions that far exceed the recommended length:

| Page | Current Length | Action |
|------|---------------|--------|
| About | ~395 chars | Cut to 155 chars |
| Services | ~476 chars | Cut to 160 chars |
| Contact | ~265 chars | Cut to 155 chars |
| Portfolio | ~442 chars | Cut to 160 chars |

Google truncates descriptions beyond ~155-160 characters, so the extra text is wasted and the truncated version may not communicate your message effectively.

### 8. Add Service Schema to Services Page
**Impact:** Medium | **Effort:** Medium | **Category:** Schema

Add `Service` structured data for each service offered:

```json
{
  "@type": "Service",
  "name": "Garage Floor Epoxy Coating",
  "description": "Professional epoxy coating for residential garage floors...",
  "provider": { "@type": "LocalBusiness", "name": "Valor Epoxy & Flooring" },
  "areaServed": { "@type": "Place", "name": "Dallas-Fort Worth, TX" },
  "serviceType": "Epoxy Flooring"
}
```

**How:** Wix → Marketing & SEO → SEO Tools → Structured Data Markup → add custom JSON-LD on the services page.

### 9. Update Custom Favicon
**Impact:** Low (branding) | **Effort:** Low | **Category:** Technical SEO

Replace the default Wix favicon with a custom icon using the Valor diamond logo.

**How:** Wix → Settings → Favicon → upload a 192x192px PNG or SVG of your logo.

---

## Medium — Fix Within 1 Month

These are optimization opportunities that will improve rankings over time.

### 10. Create a Blog with Local SEO Content
**Impact:** Very High (long-term) | **Effort:** High | **Category:** Content

Start publishing 2-4 blog posts per month targeting long-tail keywords:

**Starter topics:**
- "How Much Does Epoxy Flooring Cost in Dallas-Fort Worth? (2026 Guide)"
- "Epoxy vs. Polished Concrete: Which Is Right for Your DFW Home?"
- "5 Signs Your Garage Floor Needs Epoxy Coating"
- "Commercial Epoxy Flooring: What DFW Business Owners Need to Know"
- "How Long Does Epoxy Flooring Last? Durability Guide"
- "Metallic Epoxy Floors: Pros, Cons, and Cost in Texas"

Each post should be 800-1500 words with images, internal links to service pages, and a CTA.

### 11. Create an FAQ Page
**Impact:** High | **Effort:** Medium | **Category:** Content + Schema

Create a dedicated FAQ page with common customer questions:
- How long does epoxy flooring take to install?
- Is epoxy flooring slippery?
- Can epoxy be applied over existing concrete?
- How do I maintain epoxy floors?
- What's the difference between epoxy and polyaspartic coatings?
- Do you offer warranties?

Add `FAQPage` structured data markup to earn rich snippets in search results.

### 12. Add Customer Testimonials and Reviews
**Impact:** High | **Effort:** Medium | **Category:** Content + E-E-A-T

- Add a testimonials section to the homepage
- Include customer name, project type, and location (city)
- If you have Google Business reviews, display them
- Add `Review` or `AggregateRating` schema markup

### 13. Enrich Portfolio with Project Details
**Impact:** Medium | **Effort:** Medium | **Category:** Content

Each portfolio project page should include:
- Project description (location, scope, challenges)
- Before and after photos
- Materials/products used
- Project timeline
- Square footage
- Customer testimonial (if available)

### 14. Add BreadcrumbList Schema to All Pages
**Impact:** Low-Medium | **Effort:** Low | **Category:** Schema

Add breadcrumb structured data to help Google display breadcrumbs in search results:

```
Home > Services > Garage Floor Coatings
Home > Portfolio > Residential Garage Epoxy
```

### 15. Optimize Title Tags for Inner Pages
**Impact:** Medium | **Effort:** Low | **Category:** On-Page SEO

| Page | Current | Suggested |
|------|---------|-----------|
| About | About \| Valor Epoxy Flooring | About Valor Epoxy \| DFW Flooring Experts |
| Services | Services \| Valor Epoxy Flooring | Epoxy Flooring Services \| Dallas-Fort Worth, TX |
| Portfolio | Portfolio \| Valor Epoxy Flooring | Epoxy Flooring Projects \| DFW Before & After Gallery |
| Contact | Contact \| Valor Epoxy Flooring | Contact Valor Epoxy \| Free Quote Dallas-Fort Worth |

### 16. Add Physical Address Information
**Impact:** High (local SEO) | **Effort:** Low | **Category:** E-E-A-T

Even if you operate from a home office, consider:
- Adding your city/area to the contact page
- Creating a Google Business Profile (if not already done)
- Adding a Google Maps embed to the contact page
- Including a service area map showing DFW cities served

### 17. Update Copyright Year
**Impact:** Low | **Effort:** Low | **Category:** Technical

Footer shows "©2023" — update to "©2026" or make it dynamic.

---

## Low — Backlog

These are nice-to-have improvements.

### 18. Remove "Proudly created with Wix.com" from Footer
**Impact:** Low | **Effort:** Low | **Category:** Branding

This text reduces professional appearance. On Wix premium plans, this can be removed.

### 19. Add Location Pages for DFW Cities
**Impact:** Medium (long-term) | **Effort:** High | **Category:** Local SEO

If you serve specific cities, create dedicated pages:
- `/epoxy-flooring-dallas`
- `/epoxy-flooring-fort-worth`
- `/epoxy-flooring-plano`
- `/epoxy-flooring-arlington`
- etc.

Each page should have unique content about serving that city, not duplicate content.

### 20. Set Up Google Business Profile Optimization
**Impact:** Very High (local SEO) | **Effort:** Medium | **Category:** Off-Site

If not already done:
- Claim/create Google Business Profile
- Add all services with descriptions
- Upload project photos weekly
- Actively request customer reviews
- Post Google Business updates monthly
- Ensure NAP (Name, Address, Phone) consistency across all platforms

### 21. Monitor Core Web Vitals
**Impact:** Medium | **Effort:** Low | **Category:** Performance

Run Google PageSpeed Insights monthly to track:
- LCP (Largest Contentful Paint) — target under 2.5s
- INP (Interaction to Next Paint) — target under 200ms
- CLS (Cumulative Layout Shift) — target under 0.1

Since performance is largely controlled by Wix, focus on optimizing images and reducing unnecessary third-party widgets.

---

## Summary Timeline

| Week | Tasks | Expected Score Impact |
|------|-------|----------------------|
| Week 1 | Items 1-4 (URLs, H1, OG images) | +8 points |
| Week 2 | Items 5-9 (Schema, services content, meta, favicon) | +10 points |
| Month 1 | Items 10-13 (Blog, FAQ, testimonials, portfolio) | +12 points |
| Month 2-3 | Items 14-17 (Breadcrumbs, titles, address, copyright) | +5 points |
| Ongoing | Items 18-21 (Footer, city pages, GBP, CWV) | +6 points |

**Projected score after full implementation: 75-82 / 100**
