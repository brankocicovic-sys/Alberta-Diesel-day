# Alberta Diesel Day 2026 — ShopView Newsletter

Marketing email for ShopView customers announcing ShopView's sponsorship of Alberta Diesel Day 2026 (June 27 & 28, RAD Torque Raceway, Edmonton, AB).

## Files

- `Alberta Diesel Day Email - ShopView.html` — the newsletter, self-contained
- `uploads/` — image assets referenced by the email
  - `ShopView.svg`
  - `MHPD Logo no bg.png`
  - `Lettering Only.png` (Alberta Diesel Day lettering)
  - `mhbd-Edit.jpg` (hero background — "The Beast")

## Responsiveness

Three breakpoints tuned for inbox preview and mobile clients:

- `≤ 640px` — tablet / medium screens: tighter side padding, slightly smaller hero headline
- `≤ 520px` — phones: single-column highlights grid, scaled-down logos, smaller hero
- `≤ 380px` — small phones: hides logo dividers, stacks booth card, compact paddings

## Email-client notes

- Tested against modern clients (Apple Mail, Gmail web/mobile, iOS Mail).
- `meta color-scheme` + `supported-color-schemes` declared so dark-aware clients render correctly.
- MSO conditional swaps webfonts for system fallbacks in Outlook desktop.
- All images include `alt` text and fluid sizing.
- Inbox preview text is set inside a hidden div.

## Sending

Drop the HTML into your ESP (Mailchimp, SendGrid, etc.) and point image sources to your hosted copies of the `uploads/` files (or upload them through the ESP's media library and replace the `uploads/...` paths).
