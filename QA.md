# Quality assurance

Checked November 20, 2026.

## Local checks

- Both pages served through a local HTTP server; all seven linked internal resources returned HTTP 200.
- All relative links and fragment targets exist; IDs are unique; each page has one H1 and no skipped heading levels.
- Six strategies each include definition, objective, how it works, audience, application, KPIs and a linked real example.
- All eight assignment stages are explicit; the responsive numbered infographic includes directional connectors and a feedback path.
- Café Horizonte is labeled fictional. The case includes the service, audience, objective, strategies, channels, activities, budget, timeline, KPIs, proposed results and justification.
- The conclusion addresses selection, objectives, measurement and a contextual choice of effective strategy.
- Two photographs are local optimized WebP files, with meaningful alt text and source/license credits. No fragile image hotlinks or video dependencies.
- Semantic headings, an ordered process list, navigation labels, skip link, visible focus styles, table headers and print styling are present. Main body text starts at 16px; text and accent colors use contrasting backgrounds.
- Browser checks at 1440, 1024, 768 and 390 pixels: no horizontal page overflow. Responsive layouts, process, case, KPI table, references and cover were inspected.
- External source links were checked by HTTP or browser. FTC, REI and Unsplash blocked or timed out automated requests but their public pages loaded in Chrome. The Duolingo PDF was replaced with a reachable first-person interview hosted by Sprout Social.
- No application JavaScript, dependencies, backend, authentication, environment variables or build step.
- No absolute machine paths or development-server links in the HTML. No credentials or environment files in the project.
- Original input SHA-256 hashes were unchanged after editing copies.

## Production checks

- First public production deployment verified at https://digital-marketing-strategies-blog.vercel.app/.
- Both pages and all visual assets returned HTTP 200 without authentication.
- The cover URL was then updated to this production URL, committed, pushed to GitHub and redeployed through the Vercel connection.
- Final verification confirmed the served cover contains the actual URL, both directions of page navigation work, images load, and no horizontal overflow appears at 1440, 1024, 768 or 390 pixels. No website-origin console errors were observed.
- A new public GitHub repository and a new Vercel project were created. No pre-existing repository or Vercel project was modified.

Public cover: https://digital-marketing-strategies-blog.vercel.app/cover_page.html

## Remaining academic details

Institution, full name, student ID, course and instructor are clear placeholders because those details were not supplied. They must be completed before academic submission. Browser edits are temporary; edit the HTML source to save and publish them. No grade is guaranteed without the institution's complete rubric and review.

## Git connection status

Vercel’s existing GitHub app was granted access only to the new public repository, preserving its four previous repository selections. The new Vercel project is now connected to `ianherreraroque/digital-marketing-strategies-blog`; pushes to `main` trigger production deployment. No existing repository code or permissions were changed.
