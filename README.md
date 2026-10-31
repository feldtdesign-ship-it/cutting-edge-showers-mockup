# Cutting Edge Glass showers: website mockup

**Mockup for review. Not for publication.**

Companion to the commercial site in `../v1-code`. Same fonts, palette, header and menu. Built from the content of the current njshowerdoors.com (copied 2026-10-30).

Preview: `python3 -m http.server 8768 --directory website/showers-code`, or the `showers` entry in `.claude/launch.json`.

## How it differs from the commercial site

Same family, flipped. Same fonts (Jost body, Archivo headlines), same neon coral pop, same black-aluminum window frames, same header and menu pattern. Different mood:

- **Light page** (low-iron clear `#F5F8F7`, seafoam bands `#E3EEEC`) instead of black. A bathroom, not a building site.
- **Wider Archivo headlines** (width 112%), so it reads related but not identical.
- **Dark logo** (`img/logo-dark.png`) on the light header. The footer and the Commercial band stay dark, as a doorway back to the other site.
- **Different layouts:** photo mosaic hero, two-column intro, masonry gallery, sticky checklist, offset-shadow form.
- **Coral text** on light is the darker `#C42340` (5.4:1). The bright coral `#FF5A6E` is used only as a button fill with black text (6.5:1).

## Where each part came from

| New section | Old page |
|---|---|
| Hero, intro, facts | Home, About Us (since 1998, owner supervised, homes, commercial and boats, handrails, etched panels) |
| Three plans (in-line, neo-angle, right angle) | Service pages. Plan diagrams are new, drawn from the written descriptions |
| Glass that stays clear | Services (Enduro Shield, ShowerGuard) |
| Also made to order | Services list, Mirrors, Hardware, Glass White Boards, About Us |
| Commercial hand-off | Commercial Products |
| Gallery (40 photos, filters) | Gallery. Filters follow the old service pages (in-line, neo-angle, right angle) |
| Plan it / keeping it clear | Tips & Cleaning (two versions merged) |
| Contact | Contact Us (phone, text-a-photo, fax, email, address, by appointment) |

## Needs a decision or a check

- **Photos are hot-linked** from njshowerdoors.com. Copy them into `img/` before launch, or they vanish when the old site goes down. The originals are small (about 700 px tall), so ask Jason for full-size files.
- **Photo labels are guesses.** Alt text and filters follow the old service pages. Five photos were on no service page and sit under All only (22, 33, 34, 36, 38). Nobody has looked at each photo for accuracy.
- **Curb slope.** The old page says "5-degree (approx. 3/16" to 1/4")". Those two numbers disagree: 5 degrees is far steeper. The new page says only "pitch the curb toward the drain". Ask Jason for the right figure.
- **Hardware suppliers.** The old text reads "Portals, Luxury Hardware and Accessories C. R. Laurence, Inc". The new page names Portals and C. R. Laurence. Confirm.
- **Enduro Shield and ShowerGuard.** Copied from the old site, which is dated 2016. Confirm both are still offered, and the "up to 90%" claim.
- **Neo-angle and in-line max door widths** (26 in. and 28 in.) are from the old site.
- **Old site says "over 10 years"** in two places. Replaced with "since 1998" (About page).
- **Not carried over:** the "Site designed by MRN Web Designs" credit, the math captcha, the Visa badge, Facebook link (http://www.facebook.com/njshowerdoor). Add Facebook back if wanted.
- **Estimate form** opens a pre-filled email to sales@njshowerdoors.com. Needs a form service to send for real.
- The "Commercial glass" links point to the live commercial mockup on GitHub Pages.
