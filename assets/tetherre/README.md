# Tether RE screenshots

The `.svg` files here are placeholders so the top-level README renders cleanly
before real assets exist. Replace each one and update the `src` in `../../README.md`.

| Placeholder | Target size | What to capture |
|---|---|---|
| `hero.svg` | 1280×640 | Wide banner. App on a device, or a marketing shot. |
| `monitoring.svg` | 760×900 | Phone screenshot: SOS / duress screen or active monitoring session. |
| `verification.svg` | 760×900 | Phone screenshot: a client lookup result. **Use fake data.** |
| `productivity.svg` | 760×900 | Phone screenshot: mileage log or expense capture. |
| `dashboard.svg` | 1280×720 | Browser screenshot of the admin dashboard. |

## Before you commit anything

These images go into a **public** repo that will be the first thing people see.

- [ ] No real client names, phone numbers, or addresses
- [ ] No real agent PII
- [ ] No live GPS coordinates of an actual home
- [ ] No API keys, tokens, or internal URLs in any visible console/network pane
- [ ] No background-check results for a real person
- [ ] Cleared with Tether RE if the UI isn't already public

Screenshot with seeded demo data, not production.

## Format notes

- Prefer `.png` for UI screenshots. Rename and update the README `src` paths.
- Keep each file under ~1 MB — GitHub serves these on every page load.
- 2× resolution then downscale reads sharper on retina displays.
