Pascale,

Here's a walkthrough of the campaign site. Everything below covers what's live, what's placeholder, and what we need from you to finalize.

The site is live here:

https://agissons2026.com/

All of these domains also point to the same site:
- agissons2026.com
- agissons2026.org
- agissonsensemble2026.com
- agissonsensemble2026.org
- agissonsavecpascalerichard.com
- agissonsavecpascalerichard.org
- ensembleavecpascalerichard.com
- ensemble2026.org
- pascalerichard.com
- pascalerichard.org

You can share any of them and they'll all go to the same place.


THE SITE
--------

There are 6 pages:

1. HOME — The landing page. Hero banner with the group photo, your bio, a preview of the 3 priorities, a preview of supporters, and calls to action.

2. THE TEAM (La Liste) — The group banner photo at the top, then your featured profile with full bio, followed by a grid showing all 14 candidates with their headshots.

3. PLATFORM (Programme) — The 3 priority areas (Education, Social, Health) laid out with full detail. Your candid photo from the AFE assembly is placed between the intro and the priorities as a visual break.

4. SUPPORTERS (Soutiens) — A grid of 8 supporters showing their name and title.

5. EVENTS (Evenements) — Currently a "coming soon" placeholder that points people to Instagram. Ready to be filled in once we have dates.

6. CONTACT — Email and Instagram cards with a short message.

The site is fully bilingual. There's a FR / EN toggle in the bottom corner of every page. When someone clicks it, all text on the page switches to the other language. The browser remembers their choice so it stays that way when they go to other pages. The campaign name "Agissons Ensemble avec Pascale Richard" stays in French in both versions since it's the brand.

The site works on desktop, tablet, and mobile. On phones there's a hamburger menu for navigation.


WHAT WE NEED FROM YOU
---------------------

1. CONTACT EMAIL (high priority)
   The email address contact@ensembleny2026.org is a PLACEHOLDER. It shows up on the Contact page. Please confirm the real email address you'd like to use and we'll swap it in.

2. INSTAGRAM ACCOUNT (high priority)
   We've linked to @pascalevrichard as the Instagram handle throughout the site (Contact page, calls to action, footer). Please confirm this is the right account, or let us know if you'd prefer a dedicated campaign account (e.g. @agissons2026 or similar).

3. REVIEW THE PLATFORM PAGE (high priority)
   The Programme page expands on the 3 priority areas based on the bullet points you provided. We wrote the full descriptions and lead-in text, so please review the language carefully and let us know if anything needs adjusting or if we've misrepresented anything.

   We also placed your candid photo from the AFE assembly on this page. Let us know what you think of the photo and its placement.

4. TEAM MEMBER INFO (medium priority)
   We have headshots and names for all 14 candidates but we don't have bios, professional titles, or LinkedIn links for anyone other than you. If you'd like to add that info, please send us:
   - Professional title or role for each person
   - A short bio (2-3 sentences) if desired
   - LinkedIn profile URL or other link (optional)

   Here's the current list:
   1. Pascale Richard — Tete de liste (full bio included)
   2. Yvan Bedouet
   3. Isabelle Bonneau
   4. Luis Honsel
   5. Aissata Fernandez Taranco
   6. Gael Lambert
   7. Liliane Rubin
   8. Jean-Paul Le Boucher
   9. Martine Rubenstein
   10. Jean-Luc Streiff
   11. Line Malha
   12. Guillaume Haeringer
   13. Nicole Devilaine
   14. Joseph Papin

5. EVENTS (medium priority)
   The Events page is a placeholder right now. Once you have dates, locations, and descriptions for any events or meetings, send them over and we'll add them. The page is ready to go.

6. SUPPORTERS (low priority)
   We have 8 supporters listed. Let us know if any titles need updating, if you'd like to add or remove anyone, or if you'd like to add photos (right now it shows their initials).

   Current list:
   - Eleonore Caroit — Ministre des Francais de l'Etranger
   - Olivier Cassegrain — CEO, Longchamp
   - Francois Chateau — Avocat
   - Christian Deseglise — Fondateur de Mundi Ventures / Prof. at Columbia
   - Gwendoline Finaz de Villaine — Artiste
   - Roland Lescure — Ministre de l'Economie
   - Jean Rosanvallon — President de Corporate Angel Network
   - Christopher Weissberg — Depute des Francais d'Amerique du Nord


SUMMARY — ACTION ITEMS
-----------------------

High priority:
  1. Confirm contact email address
  2. Confirm Instagram account
  3. Review Programme page text + photo placement

Medium priority:
  4. Send team member titles / bios / links (if desired)
  5. Send event details when available

Low priority:
  6. Review supporter list and titles


Looking forward to your feedback!


------------------------------------------------------------------------
TECHNICAL DETAILS (for reference — feel free to skip or forward to anyone)
------------------------------------------------------------------------

Framework: Astro 5 with Cloudflare adapter
Hosting: Cloudflare Pages
Fonts: Maax (custom)

Pages live at the root:
  / (home), /la-liste, /programme, /soutiens, /evenements, /contact
The old site has been archived under /old/.

Images are stored in public/assets/images/ (headshots in public/assets/images/headshots/).
Logos are stored in public/assets/logos/.

To run locally: npm run dev (runs on localhost:4321)

The site is fully responsive, accessible (skip links, ARIA labels, focus styles, screen reader text, semantic HTML, proper heading hierarchy), and all alt text is language-neutral so it works in both FR and EN.

All 10 domains are configured through Cloudflare and point to the same deployment.
