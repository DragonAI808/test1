# test1 — Project Notes

## What this is
A static multi-page website for **Harbor Roasters**, a fictional specialty coffee shop in Seattle. No build tools, no frameworks — just HTML/CSS/JS files served directly. Also contains a standalone Tic Tac Toe game page.

## Tech stack
- Plain HTML5, CSS3, vanilla JavaScript
- Google Fonts: Playfair Display (brand wordmark + hero), Cormorant Garamond (body display text), Inter (body copy), JetBrains Mono (labels/tags)
- No dependencies, no package manager

## Files

**`index.html`** — Main Harbor Roasters single-page site. Sections: hero, menu, about, visit, footer. Fixed nav with scroll-triggered backdrop. All styles are inline in a `<style>` block.

**`tictactoe.html`** — Self-contained Tic Tac Toe game. Dark theme (#1a1a2e), score tracking, reset button, "← Home" link back to index.html. All logic inline.

**`Coffeeshop.jpg`** — Photo used in the About section image panel.

## Key decisions
- **Playfair Display** for all "Harbor Roasters" wordmark instances (nav, hero, footer) — chosen for a fancy/editorial feel after iterating through Space Grotesk
- **Cormorant Garamond** stays for headings and body display text (section titles, pull quotes, about lead)
- Hero height set to `88vh` (was `100vh`) and section padding reduced from `8rem` to `5rem` to reduce scrolling
- About section image panel uses `object-fit: cover` on `Coffeeshop.jpg`
- Nav hides links on mobile (< 900px) — no hamburger menu yet
- Repo: https://github.com/DragonAI808/test1

## Next steps / To-do
- [ ] Add mobile hamburger menu for nav
- [ ] Add scroll-in animations for sections
- [ ] Consider a real hero background image or video
- [ ] Add GitHub Pages deployment so the site is publicly live
