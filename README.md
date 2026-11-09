# Tshehetso Consulting website

Static, mobile-first website for Tshehetso Consulting, a social work and counselling practice in Protea Glen, Soweto.

**Status:** Draft v2, in client review. Real photos still to come: see `IMAGE-PROMPTS.md`.

## Pages

| File | Page |
|---|---|
| `index.html` | Home |
| `services.html` | Services and fees |
| `about.html` | About Counsellor Moloi and the practice |
| `contact.html` | Contact details, hours, addresses, call-back form |
| `privacy.html` | Privacy and POPIA notice |

Images are in `assets/`. Each page is self-contained HTML and CSS with no build step: open `index.html` in a browser, or serve the folder from any static host.

## Call-back form

The form on Home and Contact posts to a Make webhook, which adds a row to the private Google Sheet "Tshehetso Consulting - Call-back Enquiries". If that request fails, the visitor gets a WhatsApp button with their details filled in.

## Before going live

- Change the home page `<title>` from "DRAFT v2 - Tshehetso Consulting Website" back to "Counselling in Protea Glen, Soweto | Tshehetso Consulting".
- Add the Google Tag Manager snippet (placeholder comment in each page's `<head>`).
- Confirm `assets/og.jpg` (link-preview image) and the canonical URLs match the live domain, www.tshehetsoconsulting.co.za.
