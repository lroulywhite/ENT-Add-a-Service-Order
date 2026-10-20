# Momentus Enterprise: Add a service order (guided simulation)

A guided click-through simulation that teaches learners how to add a service order from an event function and apply Time Units to an hourly item.

- **Product:** Momentus Enterprise (captures only, never mixed with Elite or MAX)
- **Format:** one self-contained HTML file (`index.html`, about 1.2 MB). Fonts, icons, and the product UI are embedded. No network requests, no external scripts.
- **Built with:** Guided Simulation Template v2.2 (checklist bar included)

## What learners practice
1. Add a service order from a function
2. Understand the General and Items tabs
3. Add items to a service order
4. Update a service order view with Column Settings
5. Apply Time Units to an hourly item

Practice scenario: a panel discussion needs chairs, microphones, and an audio technician. The audio technician policy is a 4-hour minimum, even though the function is 1 hour.

## Run it
Open `index.html` in a browser. Use full-screen mode so the product shows at the best size. The whole 1920x1166 stage (1080 product plus 86 checklist bar) scales to fit the window.

## Embed it
Host `index.html` and place it in an iframe, for example:

```html
<iframe src="index.html" title="Add a service order simulation"
        style="width:100%;aspect-ratio:1920/1166;border:0" allowfullscreen></iframe>
```

## Repo contents
| Path | Purpose |
|---|---|
| `index.html` | The simulation |
| `screenshots/` | Title card and first step, for quick review |
| `.gitignore` | Keeps raw captures and working files out of the repo |

## Before you publish
- Demo data must be confirmed as mock by Product or Security.
- Commit sanitized output only. Never commit `raw/` captures.
- Keep the repo private unless Product and Security approve otherwise.

## Version
Source file: `ENT_Service_Order_Hours_Simulation_CHECKLIST_PREVIEW.html`, renamed to `index.html` for the repo. Update the date and tag below each time you change it.

- Template version: v2.2
- Snapshot tag: TBD
- Last updated: October 20, 2026
