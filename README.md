# BrabazonPoint public site

Static marketing pages for **brabazonpoint.com**. HTML + one CSS file. No framework. No build step.

Promise: **Complex AI. Made beautifully simple.**

Look: dark command-centre. Charcoal `#07090d` / `#0D1117`, ice-blue `#47B5FF` / `#8EC8FF` for information, restrained gold `#C9A24A` for primary actions and approvals, glass tiles, compass mark, Space Grotesk + Rajdhani.

## Files

| File | Page |
| --- | --- |
| `index.html` | Home — promise, four systems, $12 per cloud agent |
| `pricing.html` | Per-agent cloud pricing ($12/mo each) + local $70 + $7 training |
| `build.html` | Build Your Team — library, order, permissions, preview |
| `demo.html` | Watch Demo — labelled walkthrough, not a live run |
| `agents.html` | Vessel library (Signal Knight, Living Network, Toolsmith, Oracle, Pocket Titan) |
| `brabazon-agent.html` | Local agent — $70 + $7 training, free model installs, AI PC builds |
| `contact.html` | Billy Jackson, Huonville, mailto form |
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

## Pricing (do not invent)

- Cloud agents (BrabazonMind, BrabazonCode, BrabazonForge, BrabazonOS, vessel line): **$12/month each**. One agent = $12. Two = $24. Four = $48.
- Local agent (brabazonAgent): **$70** plus **$7 per added dataset or training pass**.
- Model installs are **free**.
- AI PC builds are a **custom quote**. Do not invent a price for them.
- No BrabazonWallet. That line was replaced by Forge.
- Cloud subscribe CTAs use the Stripe test Payment Link in `stripe.json`.

Build Your Team and Watch Demo are honest previews. They do not start agents, spend money, or claim a live deployment.

## Hosting

These files are not live. **brabazonpoint.com still needs DNS and a host.** Point the domain at any static file host and copy this folder to the web root. Forms use `mailto:billy@brabazonpoint.com` until a real endpoint exists.

## Copy constraints (do not drift)

- Do not invent live metrics, customer logos, prices, testimonials, or team size. Official prices: $12/mo per cloud agent; brabazonAgent $70 + $7 training; free model installs.
- The 742 pre-order figure stays on the brabazonAgent page only, until it is verified again.
- Walkthrough and sample UI must stay labelled.
- Wordmark is the text **BRABAZONPOINT** plus the compass mark.
- Do not mention Harbor Co, Tassal, Salmon Empire, The Board, Kenny, TRAWL, MERV.
