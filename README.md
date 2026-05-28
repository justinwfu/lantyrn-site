# lantyrn.app

Marketing landing page for **Lantyrn** — an offline mood lantern for iOS that
turns a five-second voice memo into a living orb of light.

Self-contained static site: a single `index.html` (inline CSS, no build step).
The orbs and app screens are recreated in CSS to match the app's design tokens
(`src/theme/tokens.ts`) and the six orb presets (`src/orb/presets.json`).

## Deploy
Deploys as a static site on Vercel (`vercel.json` enables `cleanUrls`).
Point the `lantyrn.app` domain at the project.
