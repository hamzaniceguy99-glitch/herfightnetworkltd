# Her Fight Network — women's combat sports

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `herfightnetworkltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/herfightnetworkltd.mjs`).
> To change the content, edit that file and run `node build.mjs herfightnetworkltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@herfightnetworkltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Per class / $Per month / $Never) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Her Fight Network Ltd is a women's combat sports club and network based in Eltham, south-east London, running since 2023. We teach beginners from scratch, drill technique and pads, run supervised sparring for those who choose it, and prepare members who want to compete. The rule we lead with is the one that protects your brain: if a head knock is suspected, you are removed from the session immediately and you do not return that day. The national grassroots guidance is unambiguous — if in doubt, sit them out — and it means relative rest, a graduated return, and a minimum of twenty-one days before any return to competitive contact. We will not shorten that for a fight date. Sparring is never unsupervised, coaches are DBS checked, and we do not run rapid weight cuts. Site: herfightnetworkltd.shop
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
