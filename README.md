# BrabazonPoint public site

Static marketing pages for **brabazonpoint.com**. HTML + one CSS file. No framework. No build step.

Promise: **Complex AI. Made private and simple.**

Look: dark command-centre. Charcoal `#07090d` / `#0D1117`, ice-blue `#47B5FF` / `#8EC8FF` for information, restrained gold `#C9A24A` for primary actions and approvals, glass tiles, compass mark, Space Grotesk + Rajdhani.

## Files

| File | Page |
| --- | --- |
| `index.html` | Home — private local AI, services strip, agent faces |
| `pricing.html` | Services — local AI PCs $600–$8775, install & setup, crew |
| `build.html` | Build Your Team — library, order, permissions, preview |
| `demo.html` | Watch Demo — labelled walkthrough, not a live run |
| `agents.html` | Agent library (Mind, Code, Forge, OS) |
| `brabazon-agent.html` | Local agent — pairs with a local AI PC |
| `contact.html` | Huonville, mailto form to admin@brabazonpoint.com |
| `workflows.html` | Older offer page, kept, off the main nav |
| `harnesses.html` | Older offer page, kept, off the main nav |
| `training.html` | Older offer page, kept, off the main nav |
| `site.css` | Shared command-centre styles |
| `fonts/` | Local Rajdhani + Space Grotesk (woff2) |
| `shots/` | Headless captures |

Open any HTML file in a browser, or serve the folder:

    python3 -m http.server 8080

Header, nav, and footer are duplicated on each page on purpose.

The five names on the roster are **visual identities** for the agent line. They are not extra products. The local-agent product is **brabazonAgent**.

## Offer (do not invent)

- Primary offer: **AI services** and custom **local AI PCs**.
- Local AI PC range: **$600 to $8775 AUD**. Full customise, build, install, setup.
- Private / no data leaks. Uncensored models with full local control. No remote kill-switch.
- Agent crew (BrabazonMind, BrabazonCode, BrabazonForge, BrabazonOS) is previewed on the agents page. Deploy is mailto `admin@brabazonpoint.com` with subject `Agent crew`.
- Nav label is **Services** (file remains `pricing.html`).
- Contact email everywhere: **admin@brabazonpoint.com**. No personal names on the site.
- Footer: **BRABAZONPOINT · Huonville, Tasmania · admin@brabazonpoint.com** and **AI services · Local builds**.
- No BrabazonWallet. That line was replaced by Forge.

Build Your Team and Watch Demo are honest previews. They do not start agents, spend money, or claim a live deployment.

## Hosting

GitHub Pages serves `main` at `/`. Forms use `mailto:admin@brabazonpoint.com` until a real endpoint exists.

## Copy constraints (do not drift)

- Do not invent live metrics, customer logos, prices, testimonials, or team size. Official PC range: $600–$8775 AUD.
- Do not put personal names on the public site.
- The 742 pre-order figure stays on the brabazonAgent page only, until it is verified again.
- Walkthrough and sample UI must stay labelled.
- Wordmark is the text **BRABAZONPOINT** plus the compass mark.
- Do not mention Harbor Co, Tassal, Salmon Empire, The Board, Kenny, TRAWL, MERV.
