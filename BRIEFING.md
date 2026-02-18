# Site Briefing — Agissons Ensemble avec Pascale Richard

Hi Pascale! Here's a walkthrough of the campaign site we've built for the 2026 consular elections. Everything below covers what's live, what's placeholder, and what we need from you to finalize.

---

## The Site at a Glance

The site is built with **Astro** (a modern static site framework) and hosted on **Cloudflare**. It's fast, mobile-friendly, fully bilingual (FR/EN toggle in the footer), and accessible.

There are **6 pages**:

| Page | URL path | What it does |
|------|----------|-------------|
| **Accueil** (Home) | `/v2/` | Hero banner with group photo, your bio, 3 priorities preview, supporters preview, CTA |
| **La Liste** (The Team) | `/v2/la-liste` | Group photo banner, your featured profile, grid of all 14 candidates with headshots |
| **Programme** (Platform) | `/v2/programme` | The 3 priorities (Éducation, Social, Santé) with full detail + your candid photo from the AFE |
| **Soutiens** (Supporters) | `/v2/soutiens` | Grid of 8 supporters with names and titles |
| **Événements** (Events) | `/v2/evenements` | Currently a "coming soon" placeholder, ready to be filled in |
| **Contact** | `/v2/contact` | Email + Instagram cards, message text, CTA |

---

## What We Need From You

### 1. Contact Email Address ⚠️
The email **contact@ensembleny2026.org** is currently a **placeholder** throughout the site. It appears on the Contact page and in the footer area. Please confirm the real email address you'd like to use and we'll swap it in everywhere.

### 2. Instagram Account ⚠️
We've linked to **@pascalevrichard** as the Instagram handle across the site (Contact page, CTAs, footer). Please confirm this is the correct account, or let us know if you'd prefer a dedicated campaign account (e.g. @ensembleny2026 or similar).

### 3. Events
The Événements page is a **placeholder** — it says "coming soon" and points people to Instagram. Once you have dates, locations, and descriptions for events, send them over and we'll add them. The page is already templated and ready to go.

### 4. Team Member Info
We currently have **headshots and names** for all 14 candidates. We do NOT have bios, titles, or LinkedIn links for anyone other than you. The team grid on La Liste just shows photo + name.

**If you'd like to add bios, professional titles, or links for the other 13 members, please send us:**
- Professional title / role for each person
- A short bio (2-3 sentences) if desired
- LinkedIn profile URL or other link (optional)

Here's the current list for reference:
1. **Pascale Richard** — Tête de liste *(full bio included)*
2. Yvan Bedouet
3. Isabelle Bonneau
4. Luis Honsel
5. Aissata Fernandez Taranco
6. Gaël Lambert
7. Liliane Rubin
8. Jean-Paul Le Boucher
9. Martine Rubenstein
10. Jean-Luc Streiff
11. Line Malha
12. Guillaume Haeringer
13. Nicole Devilaine
14. Joseph Papin

### 5. Programme Page — Your Review Needed
The **Programme** page expands on the 3 priority areas (Éducation, Social, Santé) based on the bullet points you provided. We wrote up the full descriptions and lead-in text — **please review the language carefully** and let us know if anything needs adjusting, rewording, or if we've misrepresented any positions.

We also placed your **candid photo from the AFE assembly** on this page as a visual break between the intro and the priority sections. Let us know what you think of its placement and whether you're happy with that photo being used there.

### 6. Supporters
We have 8 supporters listed with name + title. Let us know if:
- Any titles need updating
- You'd like to add or remove anyone
- You'd like to add photos for any of them (currently showing initials only)

Current supporters:
- Eléonore Caroit — Ministre des Français de l'Étranger
- Olivier Cassegrain — CEO, Longchamp
- François Château — Avocat
- Christian Deseglise — Fondateur de Mundi Ventures / Prof. at Columbia
- Gwendoline Finaz de Villaine — Artiste
- Roland Lescure — Ministre de l'Économie
- Jean Rosanvallon — Président de Corporate Angel Network
- Christopher Weissberg — Député des Français d'Amérique du Nord

---

## How the Bilingual Toggle Works

There's a **FR / EN** toggle button in the footer of every page. When a visitor clicks it:
- All text on the page switches between French and English
- The preference is saved in the browser, so it persists across page visits
- The HTML `lang` attribute updates accordingly

Every piece of visible text has been translated. The campaign name "Agissons Ensemble avec Pascale Richard" stays in French in both versions (it's the brand).

---

## What's Already Done

- Full responsive design (desktop, tablet, mobile)
- Mobile hamburger menu navigation
- Hero banner with group photo as full-bleed background on desktop, stacked layout on mobile
- Your bio section on the homepage with avatar, key facts, and link to the Renaissance interview
- All 14 headshots wired into the team page
- Tricolore stripe (blue-white-red) at top and bottom of every page
- Renaissance logo in header and footer
- Accessibility: skip link, ARIA labels, focus styles, screen reader text, semantic HTML, proper heading hierarchy
- All alt text is language-neutral (works in both FR and EN)
- Proper `target="_blank"` + `rel="noopener noreferrer"` on all external links

---

## Tech Notes (for reference)

- **Framework**: Astro 5 with Cloudflare adapter
- **Hosting**: Cloudflare Pages
- **Fonts**: Maax (custom)
- **Dev command**: `npm run dev` (runs locally on localhost:4321)
- **All pages live under `/v2/`** — this allows running alongside any existing site
- **Images**: stored in `public/assets/images/` (headshots in `public/assets/images/headshots/`)
- **Logos**: stored in `public/assets/logos/`

---

## Summary of Action Items

| # | Item | Priority |
|---|------|----------|
| 1 | Confirm contact email address | High |
| 2 | Confirm Instagram account | High |
| 3 | Review Programme page text + photo placement | High |
| 4 | Send team member titles / bios / links (if desired) | Medium |
| 5 | Send event details when available | Medium |
| 6 | Review supporter list + titles | Low |

Looking forward to your feedback!
