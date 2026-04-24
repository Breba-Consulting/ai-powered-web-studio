Background  
- Consulting for easily updatable, conversion-focused websites/landing pages.  
- Emphasis on client control, full asset ownership, no vendor lock-in, optional AI/agents/tools.  
- Sites operate without ongoing consultant involvement and support handoff to other developers or AI tools.  
- Websites positioned as tools that reduce ongoing effort for owners.

Website Purpose & Positioning  
- Marketing/lead-generation focus for automated, easily updatable sites and workflows.  
- Emphasis on automation, workflows, conversions, analytics, SEO performance, and strong search rankings.  
- Messaging centered on customer problems and outcomes.  
- Agents/tools positioned as optional enablers; easy content updates via chat.  
- Services include AI agent integration, LLM recommendation strategy, and SEO.  
- Assumption that LLM-sourced leads are higher quality.  
- Fast delivery timelines and future-facing automation positioning.  
- Targeting service businesses (e.g., spa, landscaping, limo).  
- Hero messaging emphasizes $0 maintenance cost.

Visual & UX Preferences  
- Dark, modern, polished productized SaaS/agency aesthetic.  
- Clean typography with strong hierarchy; system UI sans-serif only.  
- Blue and purple accents.  
- Preference for numbered elements over icons/badges.  
- All section headings and subheadings centered.  
- Navbar primary CTA visually restrained on mobile.  
- Navbar brand text larger on mobile (1.25rem).  
- No social media icons in footer.  
- Logo combines image and gradient text; logo text always fully readable; on mobile text hides on scroll while image remains, desktop keeps both.  
- Hero CTAs full-width on small mobile, with consistent margins and 1.5rem text padding.  
- Calendly modal minimal and focused, with clear loading feedback.  
- Hero section full viewport height with centered content.  
- Default header height 80px.  
- Preference for aesthetically pleasing line wrapping, avoiding single-word lines.  
- Key CTA labels remain on a single line and not compressed.  
- Benefits callout text visually simple, without heavy emphasis.  
- Promotional callouts visually consistent with the “How it works” long card style.  
- Key promotional CTA copy: “Claim This Offer”.

Layout & Interaction Decisions  
- Single-page layout.  
- Hero main heading visually constrained with gradient and entrance animation.  
- Hero includes rotating checklist element.  
- Rotating checklist animation coordinated with icon font readiness (or reasonable timeout).  
- Hero title text and navbar logo text revealed only after font loading is confirmed.

Pricing & Offering Decisions  
- Pricing shows promotional vs original amounts.  
- Entry-level professional website offering at a defined price point with contact capability.  
- Mid-tier identified and visually treated as most popular.  
- “Most popular” label visually emphasized but not overwhelming and positioned to avoid title overlap.  
- Top-tier uses custom pricing but remains visually consistent.  
- Buttons across comparable pricing cards vertically aligned.  
- Free hosting included.

Technical & Navigation Constraints  
- Single HTML file containing markup, styles, and scripts.  
- Contact handled via third-party form service with spam protection.  
- Navbar contains only “Pricing” and “Let’s Go”.  
- Desktop: navbar links/CTA initially hidden and revealed with animated focus transition aligned to hero CTA reveals.  
- Mobile: navbar always shows “Pricing” and “Let’s Go”; no hamburger menu.  
- Footer includes privacy link via relative path and credits Breba as maker, highlighting breba.app as build tool.  
- All primary CTAs open a Calendly modal.  
- Calendly calendar fills modal width; mobile and tablet views use effectively full-screen height.  
- Calendly script loaded lazily after primary content.  
- Calendly event tracking based on event-type views.  
- Icon font loaded via shared font resource with curated icon set.  
- CSS loading prioritized so core styles are render-blocking; fonts load non-blocking.  
- Analytics via Umami; Google Analytics excluded.

SEO & Metadata Decisions  
- Primary domain and canonical URL: https://breba-consulting.com/  
- Robots: index, follow.  
- Meta description shared across standard meta, Open Graph, and Twitter.  
- Open Graph: title matches page title; description matches meta; dedicated OG image; URL uses canonical.  
- Twitter Card: summary_large_image with same title, description, and image as Open Graph.  
- No social/profile URLs in structured data.  
- Schema.org JSON-LD for WebSite and Organization with “Breba Consulting”, canonical URL and logo, description matching meta, worldwide area served, topics of expertise, founder, and schedule/contact actions; no public contact details.  
- Main H1 maintains readable whitespace even when visually split.