# Otago Kidney Society — website

The website for the **Otago Kidney Society Inc.**, a registered charity supporting people affected by kidney disease in Otago, New Zealand.

Live site: _(GitHub Pages URL once enabled)_ · Domain: oks.nz

---

## What this is

A plain static website — just HTML and CSS. No build step, no framework, no database. You can open any `.html` file directly in a browser to preview it, and it can be hosted anywhere.

## Pages

| File | Page |
|---|---|
| `index.html` | Home |
| `about.html` | About the Society, our purpose, committee, governance |
| `support.html` | Support for patients & whānau, membership, resources |
| `events.html` | Events, lunches, World Kidney Day, AGM, news |
| `newsletters.html` | Newsletter archive (downloadable PDFs) |
| `donate.html` | Donations, bequests, fundraising partners |
| `contact.html` | Contact details and how we can help |

## Folders

- `styles.css` — all site styling, shared by every page
- `images/` — logo and photographs
- `forms/` — membership application form (PDF)
- `newsletters/` — quarterly newsletter archive (PDF)

## How to make changes

**Editing text:** open the relevant `.html` file in any text editor, find the words you want to change, and change them. Everything between `<p>` and `</p>` is a paragraph of text.

**Changing colours or fonts:** everything visual lives in `styles.css`. The colours are set at the very top under `:root` — change a hex code there and it updates across the whole site.

**Adding a newsletter:**
1. Put the PDF in the `newsletters/` folder, named like `oks-newsletter-spring-2026.pdf`
2. Open `newsletters.html` and copy an existing `<div class="event">` block
3. Update the season, year, description and file name in your copy

**Adding a committee member:** open `about.html`, find the `<div class="committee">` section, and copy one of the `<div class="person">` blocks.

**Updating contact details:** the address, email and phone appear in the footer of every page, so they need changing in all seven `.html` files. Search for `info@oks.nz` to find them.

## Contact

Otago Kidney Society Inc.
36 Prestwick Street, Māori Hill, Dunedin 9010
info@oks.nz · 027 454 3512

Registered charitable entity under the Charities Act 2005. Patron: Katherine Rich.
