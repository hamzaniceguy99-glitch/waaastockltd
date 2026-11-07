# WAAA Stock — wholesale & online retail

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `waaastockltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/waaastockltd.mjs`).
> To change the content, edit that file and run `node build.mjs waaastockltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@waaastockltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Declined) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
WAAA Stock Ltd is a London company trading since March 2021 in non-specialised wholesale and in retail sale over the internet. We supply trade accounts, sell direct to customers online, and move clearance and overstock lines. One part of this trade changed recently and a great many small sellers have not noticed. Under the UK packaging producer responsibility rules, the disposal cost of packaging is charged to the obligated producer, and fees have been invoiced since autumn 2025. An organisation is caught once its annual turnover reaches one million pounds and it is responsible for more than twenty-five tonnes of packaging in a year; above two million pounds and fifty tonnes it registers, reports twice a year and pays. The obligated party is normally the brand owner, which means anyone selling goods under their own name. The detail that surprises people is that selling through an online marketplace does not transfer the obligation for a UK-established seller: the platform carries it only for sellers based outside the UK. So we record the weight and material of everything we ship, and we choose packaging that is recyclable, because from 2026 the fee itself depends on that. Site: waaastockltd.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
