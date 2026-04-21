Background  
- Consulting for easily updatable, conversion-focused websites/landing pages.  
- Emphasis on client control, no vendor lock-in, optional AI/agents/tools.

Website Purpose & Positioning  
- Marketing/lead-generation for automated, easily updatable sites and workflows.  
- Focus on automation, workflows, conversions, and analytics.  
- Messaging centered on customer problems and outcomes.  
- Agents/tools positioned as optional enablers; core AI agent for content updates.  
- Fast delivery timelines.  
- Future-facing automation positioning.

Visual & UX Preferences  
- Dark, modern, polished productized SaaS/agency aesthetic.  
- Clean typography with strong hierarchy; primary typeface Inter.  
- Blue and purple accents.  
- Preference for numbered elements over icons/badges.  
- All section headings and subheadings centered.  
- Navbar primary CTA visually restrained on mobile.  
- No social media icons in footer.  
- Logo combines image and gradient text; mobile hides text logo on scroll, desktop keeps both; logo text fully visible.  
- Hero CTAs full-width on small mobile.  
- Calendly modal with minimal ancillary text.  
- Hero section full viewport height with centered content.  
- Hero subheading preserved as-is.

Layout & Interaction Decisions  
- Single-page layout.  
- Hero main heading visually constrained with gradient and entrance animation.  
- Hero includes rotating checklist element.

Pricing & Offering Decisions  
- Pricing includes promotional pricing vs original.  
- Mid-tier identified as most popular.  
- Top-tier uses custom pricing but visually consistent with other tiers.  
- Buttons in comparable cards vertically aligned.

Technical & Navigation Constraints  
- Single HTML file including markup, styles, and scripts.  
- Contact form submits to external API endpoint.  
- Navbar contains only “Pricing” and “Let’s Go”.  
- Desktop: navbar links/CTA initially hidden and revealed via animated focus transition aligned with hero CTAs, with distinct reveals.  
- Mobile: navbar always shows “Pricing” and “Let’s Go”; no hamburger.  
- Footer privacy link uses relative path.  
- All primary CTAs open a Calendly modal.  
- Calendly calendar fills modal width on all devices.  
- Mobile phones: Calendly uses full screen height.  
- Tablets: Calendly uses expanded, mobile-like full-screen height and space.  
- Material Symbols font loaded via shared Google Fonts URL with icon_names parameter in alphabetical order.  
- Inter font loading prioritized over other fonts; Inter uses font-display: swap.  
- External CSS and font stylesheets (including Google Fonts and Material fonts) loaded in a non-blocking, performance-optimized way.  
- Analytics handled via Umami; Google Analytics excluded.

SEO & Metadata Decisions  
- Primary domain https://breba-consulting.com/  
- Canonical URL https://breba-consulting.com/  
- Robots: index, follow.  
- SEO title: “We design and build high-converting websites and landing pages, then equip you with the tools that let you focus on your work and not your website.”  
- Meta description equals SEO title.  
- Open Graph: title matches page title; description matches meta; dedicated OG image; URL uses canonical.  
- Twitter Card: summary_large_image with same title, description, and image as Open Graph.  
- No social/profile URLs exposed in structured data.  
- Schema.org: WebSite and Organization JSON-LD with name “Breba Consulting”, canonical URL, specified logo asset, description matching meta, worldwide area served, topics of expertise, founder, and actions for scheduling and contacting; no public contact details.  
- Main H1 visually preserves readable whitespace even when split across multiple spans.