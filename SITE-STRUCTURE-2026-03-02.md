# Site Structure - Valor Epoxy

Date: 2026-03-02  
Model: Local service SEO (`service x location`)

## Proposed URL Hierarchy

- `/`
- `/about`
- `/contact`
- `/get-a-quote`
- `/services/`
  - `/services/epoxy-flooring`
  - `/services/garage-floor-coatings`
  - `/services/commercial-epoxy-flooring`
  - `/services/industrial-floor-coatings`
  - `/services/metallic-epoxy`
  - `/services/polyaspartic-coatings`
  - `/services/concrete-polishing`
  - `/services/concrete-staining`
  - `/services/flake-quartz-systems`
- `/locations/`
  - `/locations/dallas`
  - `/locations/fort-worth`
  - `/locations/plano`
  - `/locations/frisco`
  - `/locations/arlington`
  - `/locations/mckinney`
  - `/locations/irving`
  - `/locations/grapevine`
  - `/locations/southlake`
- `/portfolio/`
  - `/portfolio/{project-slug}`
- `/case-studies/`
  - `/case-studies/{service-city-slug}`
- `/resources/`
  - `/resources/epoxy-vs-polyaspartic`
  - `/resources/how-long-epoxy-last-texas`
  - `/resources/garage-floor-coating-cost-dfw`
  - `/resources/concrete-prep-checklist`
- `/faqs`
- `/reviews`

## Information Architecture Rules

- One canonical URL per unique intent.
- Every service page links to top 6 locations; every location page links to top 6 services.
- Portfolio and case studies must link back to the relevant service and location hub.
- Use breadcrumbs and contextual links to avoid orphaned pages.

## User Journey Paths

- **Residential path:** Home -> Garage Floor Coatings -> City page -> Quote.
- **Commercial path:** Home -> Commercial/Industrial service -> Case study -> Quote.
- **Research path:** Resource article -> Relevant service page -> FAQ -> Quote.

## Internal Linking Strategy

- Home page links to all top service hubs and 4 priority locations.
- Services index links to all child services and relevant case studies.
- Locations index links to all child locations and city-specific proof blocks.
- Add "related services" and "nearby areas" components to increase crawl depth.

## Sitemap Design

- `sitemap-core.xml` (core pages)
- `sitemap-services.xml`
- `sitemap-locations.xml`
- `sitemap-portfolio.xml`
- `sitemap-resources.xml`

## Page Quality Gates

Each money page must include:
- Unique title/H1 aligned to service and city intent.
- 600-1200+ words of unique, non-spun content.
- Local proof block (recent project, testimonial, or result).
- FAQ section with schema eligibility.
- Clear CTA (call + quote form).
- Service/process section and warranty/guarantee statement where applicable.

## Crawl and Index Health Targets

- 0 orphan pages in monthly crawl.
- <3 click depth for top 80% of revenue pages.
- Canonical and internal link consistency at template level.
- All indexed pages mapped to an intent bucket (service, location, proof, resource).
