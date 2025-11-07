---
viewport: 1440x900
grid:
  columns: 12
  column_width: 72
  gutters: 24
  margins: 120
baseline_grid: 8
---

# Layout Structure
- Desktop viewport locked to 1440 px width with a 120 px padding on left/right; content spans 1200 px.
- 12-column grid with 72 px columns and 24 px gutters; hero and content sections align to columns.
- Baseline grid set to 8 px increments; typography and spacing snap to this rhythm.
- Vertical section spacing: 96 px above/below major sections, 64 px for subsections.
- Fixed header overlays content with 80 px height; page below starts with compensating top padding (80 px + 24 px breathing room).

# Header (Fixed)
- Height 80 px, full-width bar with semi-transparent deep green (#10261f / 90%) background over hero imagery, transitions to solid on scroll.
- Left (columns 1-3): `ETCP` logomark wordmark combination, white, 24 px height; clicking scrolls to top.
- Center (columns 4-9): primary nav links with 18 px font, uppercase, 24 px letter spacing:
  1. Impact Ledger
  2. Verified Journeys
  3. Science Partners
  4. Methodology
  5. Transparency Reports
- Right (columns 10-12):
  - Icon button: search (magnifier) toggles modal search overlay.
  - Icon button: user profile silhouette for login/signup.
  - CTA button `Plan a Proof-First Trip` (40 px height, 16 px font, gradient green #22b573 to teal #11867a) with subtle drop shadow; sticky styling on scroll.

# Hero Section
- Height 720 px (9 columns tall), full-bleed background video loop showing verifiable eco-restoration projects with overlayed dark green gradient (top 0.85 opacity to bottom 0.4).
- Left content block spans columns 1-7, vertically centered.
  - Headline (H1, 56 px, bold, white): `Travel that Audits Itself.`
  - Subheadline (24 px, 400 weight, max width 520 px, white 85% opacity): `ETCP is the eco-tourism platform that proves every restoration claim with immutable evidence—so you can explore without funding greenwashing.`
  - Primary CTA button `Audit Destinations` (52 px height, 20 px font, white text on #22b573) aligned baseline.
  - Secondary CTA `See How We Verify` (ghost button, white border, 52 px height) positioned 16 px to the right; arrow icon to indicate deep dive.
- Proof Strip at bottom of hero (stretched columns 1-12, 104 px height, dark overlay).
  - Displays rolling metrics: `87,420 tonnes CO₂ verified`, `418 local scientists contracted`, `3.2M data points logged`, each with tooltip icon revealing data source.
  - Metrics separated by thin vertical dividers aligned to grid gutters.

# Carbon Impact Calculator Widget
- Positioned overlapping hero's lower right (columns 8-12), glassmorphic card (background rgba(255,255,255,0.9), blur 20).
- Size: 360 px width × 420 px height; floating with subtle drop shadow.
- Header row: `Estimate Your Trip’s Verified Offset` (20 px bold, dark green) with `Last audit: <timestamp>` microcopy (12 px, grey).
- Form inputs:
  - Trip duration slider (1-21 days) with numeric input; slider track uses gradient aligning with brand palette.
  - Destination dropdown pre-populated with verified eco-regions; includes badges indicating data freshness (e.g., `Updated 9 days ago`).
  - Group size stepper with plus/minus buttons.
  - Accommodation type segmented control (Eco-lodge, Community Homestay, Research Expedition).
- Dynamic output panel (fills bottom 160 px):
  - `Projected CO₂ drawdown:` large numeric display (36 px) with `kg` label; value animates as inputs change.
  - `Verification evidence:` mini-carousel of 3 icons (blockchain hash, satellite imagery, third-party lab) each clickable to open modal.
  - CTA `View supporting data` as tertiary link styled with underline.
- Widget includes reassurance microcopy `Powered by TerraVeritas™ measurement protocol` with partner logo.

# Mission Proof Section
- Top padding 96 px from hero proof strip; background white.
- Section intro (columns 1-6):
  - Eyebrow label `Why ETCP exists` (14 px uppercase, tracking 180).
  - H2 `No vague promises. Only verifiable restoration.` (44 px).
  - Body copy (18 px, 60% width) explaining multilayer verification (blockchain ledger + independent audits + community validation).
- Evidence Pillars grid (3 cards across, columns 1-12, guttered):
  1. `Immutable Impact Ledger` – includes miniature ledger screenshot placeholder, bullet list of audit partners, footnote `Publicly queryable`.
  2. `Live Ecological Sensors` – line chart placeholder, copy describing real-time satellite + IoT feed.
  3. `Community Stewardship Scores` – testimonial snippet placeholder with local partner photo circle.
- Each card features `View Proof` micro-CTA linking to modal.

# Featured Verified Journeys
- Background light grey (#f4f7f5); padding 96 px top/bottom.
- Section header centered (columns 1-12): eyebrow `Proof-first itineraries`, H2 `Journeys with receipts`, supporting copy (18 px) encouraging exploration.
- Horizontal carousel occupying columns 1-12 with 3 cards visible (380 px width each).
  - Each card includes hero image placeholder, badge `Scientifically audited`, impact stats strip (CO₂ offset, biodiversity uplift), CTA `Inspect Verification`.
- Carousel controls anchored outside main grid (left/right arrows at ±32 px).

# Transparency Dashboard Preview
- Background white, spans columns 1-12 with 96 px spacing.
- Split layout: left columns 1-6 features screenshot placeholder of dashboard showing ledger records timeline.
- Right columns 7-12 include bullet list:
  - `Real-time audit trail per booking`
  - `Compiled verification dossiers`
  - `Third-party dispute resolution`
- Secondary CTA `Explore the full dashboard` (ghost style) plus supporting microcopy `Updated every 6 hours by independent auditors`.

# Partner & Certification Wall
- Dark background #0b1d18; 80 px vertical padding.
- Grid of partner logos (4 columns × 2 rows) in white monochrome, spaced evenly.
- Above grid (columns 1-12 center-aligned): eyebrow `Independently verified by`, H2 `Global science and policy partners`.
- Footer microcopy `Regenerative Tourism Council Member • Science Based Targets compliant`.

# Testimonials & Skeptic Proof
- Background gradient from #ffffff to #e8f1ed; 96 px padding.
- Two-column layout:
  - Left (columns 1-6): rotating quote slider featuring skeptical traveler testimonials converted into advocates; include data callouts showing quantified impact.
  - Right (columns 7-12): proof tiles listing `Audit Report PDFs`, `Open-source Methodology`, `Ask the Scientist` with micro icons and link chevrons.

# Final Assurance CTA
- Narrow banner (height 220 px) with background overlaying satellite imagery.
- Centered copy: H2 `Ready for a trip that proves its impact?`, supporting copy referencing immutable records, CTA `Browse Verified Expeditions`.
- Secondary note `No paywall—browse full evidence before booking`.

# Footer Preview (fold hint)
- 60 px tall strip hinting at footer content with arrow indicator encouraging scroll.
- Includes quick links `Impact Ledger`, `Contact Audit Team`, `Download Methodology PDF`.
