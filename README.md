# Tshehetso Consulting website

Static, mobile-first website for Tshehetso Consulting, a social work and counselling practice in Protea Glen, Soweto.

**Status:** Final, shared with the client. Live on GitHub Pages: https://anelekunene-lab.github.io/TshehetsoConsulting/

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

- Add the Google Tag Manager snippet (placeholder comment in each page's `<head>`).
- Confirm `assets/og.jpg` (link-preview image) and the canonical URLs match the live domain, www.tshehetsoconsulting.co.za.

## Photo credits

Service and "What to expect" photos are from [Pexels](https://www.pexels.com/license/) (free for commercial use, no attribution required), except two generated with Gamma.

| File | Source |
|---|---|
| `svc-stress.webp`, `expect-medical.webp` | Generated with Gamma AI |
| `svc-grief.webp` | Pexels photo 7239089 |
| `svc-trauma.webp` | Pexels photo 5699489 |
| `svc-family.webp` | Pexels photo 12788362 |
| `svc-parenting.webp` | Pexels photo 9870222 |
| `svc-youth.webp` | Pexels photo 36729613 |
| `svc-gbv.webp` | Pexels photo 8996007 |
| `svc-substance.webp` | Pexels photo 7579301 |
| `svc-hiv.webp` | Pexels photo 10665639 |
| `svc-group.webp` | Pexels photo 8556340 |
| `svc-advocacy.webp` | Pexels photo 9870140 |
| `expect-hours.webp` | Pexels photo 14299948 |
| `expect-online.webp` | Pexels photo 27176547 |
| `expect-languages.webp` | Pexels photo 30689324 |
| `expect-inperson.webp` | Pexels photo 5234687 |
| `callback-home.webp` | Pexels photo 8279490 |
| `about-office.webp` | Pexels photo 28461045 |

Photo pages: `https://www.pexels.com/photo/<id>/`. Pexels photos show models, not clients of the practice.
