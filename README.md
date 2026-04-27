[README.md](https://github.com/user-attachments/files/27137087/README.md)
# Maestro Kanvas

> The visual workspace for the Maestro family.

Maestro Kanvas is a single-file web app that combines a whiteboard, a wiki, a kanban board, and four other views into one tool — with AI assistance powered by Claude.

🌐 **Live site:** [maestro-kanvas.pages.dev](https://maestro-kanvas.pages.dev)

Part of the Maestro Connect ecosystem alongside Maestro Fraud, Maestro Marketing, Maestro Identity, Maestro KYC, Maestro UPG, Maestro CallMe, and Maestro Desk.

---

## What it does

Seven views of the same workspace, switchable from the top:

- **Canvas** — sticky notes, shapes, text, images, freehand pen drawing
- **Docs** — structured wiki pages with embeds and AI summaries
- **Board** — kanban with status columns
- **Calendar** — month grid with coloured event tags
- **Timeline** — Gantt-style swimlanes by discipline
- **Mind map** — visual tree with branch themes and AI expansion
- **Database** — filterable table view of tasks

Plus dark and light modes (dark default), mobile-responsive layout, and a context menu for changing colours, fonts, sizes, links, and tags on any element.

## AI features

Connect a [Claude API key](https://console.anthropic.com/settings/keys) once (settings cog in the top bar) to unlock four AI actions:

- **Summarise** any document into 3 bullets
- **Cluster** sticky notes into themes automatically
- **Convert** ideas into actionable kanban cards
- **Expand** any mind map node into sub-branches

Your API key is stored only in your browser. Nothing is sent to any server we run — calls go directly to Anthropic.

## Design

Visual language matches the Maestro family:

- Pure-black canvas (dark mode) or lavender-white (light mode)
- Indigo → blue → cyan gradient as the brand element
- Inter throughout for tight modern typography
- Per-product colour-coded tags
- Glow effects and soft hover lifts on interactive elements

## How it's built

Single HTML file, no framework, no build step. Just open `index.html` in a browser.

- Vanilla HTML, CSS, and JavaScript
- Fonts loaded from Google Fonts (Inter, JetBrains Mono, Caveat)
- Stock images from Unsplash
- AI calls direct to the Anthropic API via CORS

## Deployment

Hosted on **Cloudflare Pages**, auto-deployed from this GitHub repo. Push to `main` and the site updates within ~30 seconds.

## Getting your own AI key

1. Go to [console.anthropic.com/settings/keys](https://console.anthropic.com/settings/keys)
2. Create an API key (free $5 credit on signup)
3. Open Maestro Kanvas, click the settings cog
4. Paste the key, hit save

A typical AI action costs less than $0.001 with Claude Haiku, so the free credit lasts thousands of calls.

## Author

Built by Jodi Kidd at STech Group, with iGaming and compliance use cases in mind. The seeded content reflects a real Q2 reactivation campaign for the Brazilian market.

## License

Personal project — feel free to fork and adapt for your own team.
