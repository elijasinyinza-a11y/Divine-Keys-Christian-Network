# Divine Keys Christian Network

A Kingdom platform equipping believers with AI-powered tools for scripture study, book publishing, business coaching, and global missions.

**Live site:** https://divine-keys-christian-network.vercel.app

---

## Pages

| File | Description |
|------|-------------|
| `landing.html` | Public landing page — entry point for new visitors |
| `signin.html` | Sign in |
| `register.html` | Create account |
| `index.html` | Home / Dashboard (logged-in) |
| `sessions.html` | Session history |
| `sophia.html` | Sophia AI agent session |
| `scribe.html` | Scribe AI agent session (book publishing + cover studio) |
| `bible-study.html` | Bible Study Companion |
| `vod.html` | Moments of Wisdom — video on demand |
| `city-builders.html` | City Builders Circle — community & accountability |
| `bookstore.html` | Divine Keys Publishing bookstore |
| `missions.html` | Global Missions |
| `donate.html` | Give to Missions |
| `profile.html` | User profile & settings |
| `upgrade.html` | Upgrade to Pro |
| `admin.html` | Admin dashboard (restricted — not for public sharing) |

## Agents

- **Sophia** — scripture study, business coaching, missions intelligence, accountability
- **Scribe** — book publishing, manuscript drafting, cover studio, DOCX export

## Deployment

Static HTML — no build step required. Push to `main` branch and Vercel auto-deploys.

`vercel.json` routes the root URL to `landing.html`.
