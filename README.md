# Chris Lee Bergstrom

**AI-native full-stack engineer** · Portland, OR · remote

I don't hand-write code. I architect, specify, and verify; the agents type. Claude Code builds, Codex reviews, each model runs the other's tests, and CI decides what ships. Before software, I spent twenty years running live events, where work ships on show day or it doesn't ship.

---

### Try it now (no signup)

| | What it is | Try it |
|---|---|---|
| ⚡ **Byte Mail** | An AI assistant that lives entirely in email. No app, no login. Outside users found it on their own and use it every day. | Email **byte@firstlyte.co** · [firstlyte.co](https://firstlyte.co) |
| ♟️ **Chester** | A chess app with an AI companion that comments on your game as you play. Custom minimax engine, Elo, Stripe, PWA. | [chesterchess.com](https://www.chesterchess.com) |
| 💬 **EVE** | The AI concierge on my site. The site has been rebuilt with each new model generation. | [chrisleebergstrom.com](https://chrisleebergstrom.com) |
| 🔊 **Beacons** | Live noise-compliance monitoring for venues. Used on stage by a professional symphony orchestra. | [beaconsio.com](https://beaconsio.com) |
| ⛽ **Fuel Estimator** | A free tour-bus fuel-cost calculator for tour managers, priced per state. | [fuel-estimator.onrender.com](https://fuel-estimator.onrender.com) |
| 🎸 **The Underground** | A playable venue-management game built end to end with agents. | [Play it](https://underground-venue-manager.onrender.com) |

---

### Code you can read

- **[byte-mail](https://github.com/Nxtvanhalen/byte-mail)**: the production code behind Byte. Bun + Hono, DeepSeek with model routing, Redis threading, a safety layer for sensitive topics, privacy deletion confirmed from the sender's own inbox, a nightly AI self-review, and 560+ tests. All of the test data is made up.
- **[ai-chess](https://github.com/Nxtvanhalen/ai-chess)**: Chester. Next.js, Supabase with RLS, Stripe, and Claude streaming commentary over SSE.
- **[Website](https://github.com/Nxtvanhalen/Website)**: My site and EVE. Next.js, nonce-based CSP, WCAG 2.1 AA.

Most of my day-to-day work is in private client and company repos. The contribution graph counts it, but you can't open those repos.

---

### How I build

- **Two models, adversarial.** Claude Code writes and Codex reviews. Findings loop between them until they're resolved, and each model runs the other's tests before anything merges.
- **Context lives in the repo.** CLAUDE.md files, scope docs, decision logs, and blind-spot logs, so the next agent (or person) starts from a one-line goal and doesn't have to guess.
- **Checks instead of diff-reading.** Tests, CI, database advisors, and staged deploys decide what ships.
- **Every layer.** Hosted and local models, MCP servers, Postgres schemas with RLS, native iOS, ESP32 hardware, and calibrated microphones.

---

### Recent work

- **Beacons** (co-founder & CTO): I built the whole platform alone. That covers the Swift iOS app with on-device DSP, the Next.js dashboard, Supabase/Postgres, ESP32 sensor nodes over Thread/MQTT, and Sentinel, an AI ops agent in Slack.
- **Eventric / Master Tour**: an 8-app TypeScript extension to a 25-year-old SaaS platform. The first 17 days produced about 300 commits, a 51-table schema, 148 RLS policies, and 491 tests.
- **Glytch**: my personal multi-agent assistant. It has a per-turn model router and two-way voice on ESP32 hardware, and it's slowly getting a robot body.

---

### Stack

`TypeScript` `React` `Next.js` `Bun` `Hono` `Node.js` `Swift` `Python`
`PostgreSQL` `Supabase` `pgvector` `Redis` `Stripe`
`Claude API` `Claude Code` `Codex` `MCP` `DeepSeek` `Ollama`
`Render` `Vercel` `Cloudflare` `Sentry` `GitHub Actions` `ESP32` `MQTT`

---

### Contact

[chrisleebergstrom.com](https://chrisleebergstrom.com) · [LinkedIn](https://linkedin.com/in/chris-bergstrom) · chrisleebergstrom@gmail.com
