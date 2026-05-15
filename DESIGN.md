# Balam Group Design System

## Color Palette
- **Navy (Primary):** #0F2141 — trust, stability, authority
- **Gold (Accent):** #C9922A — premium, approachability, warmth
- **Warm Grey (Secondary):** #94A3B8 — neutral, readable
- **White:** #FFFFFF — clean, minimal
- **Light BG:** #F5F6F8 — section breaks, soft separation

## Typography
- **Serif (Display):** Libre Baskerville — headings, premium positioning
- **Sans-serif (Body):** Inter — readable, modern, accessible
- **H1:** 3.5rem, regular weight
- **H2:** 2.5rem, regular weight
- **Body:** 15–17px, 1.8 line-height

## Spacing & Grid
- Container max-width: 960px
- Section padding: 4–6rem vertical
- Component gap: 1.5–2rem
- Rhythm varies between sections

## Components
- **Property Cards:** 3-column grid, image + overlay badge, lifestyle copy
- **Team Cards:** Photo + bio, alternating layout
- **Buttons:** Primary (gold), secondary (navy outline)
- **Testimonials:** Simple, left-aligned, no heavy styling

## Motion Strategy
- **Entrance:** Fade in + subtle slide-up (fade-in-up) on scroll
- **Scroll Triggers:** Stagger delays for card grids (0s, 0.1s, 0.2s pattern)
- **Hover:** Property cards — slight elevation, shadow expand
- **Micro:** Button hover state, form focus states

## Current Animation State
- CSS fade-in-up class exists but not triggered on scroll
- Hamburger menu exists but JavaScript event listener missing
- CTA button (chat) spans full width at bottom — needs repositioning
