I build production web platforms and AI agent systems — most recently a multi-tenant website/booking engine serving paying small-business clients, a self-learning AI recruiting-outreach agent (Alma), and a self-hosted real-time multiplayer game.

## Flagship (production, closed-source)

- **[GrowZone](https://growzonecy.com)** — multi-tenant Next.js/Supabase platform serving production websites for small businesses in Cyprus. Closed-source: real paying clients run on it.
- **Rantevouu** — salon booking and CRM software, live for two paying retainer clients. Closed-source, same reason.

## Projects

- **[Alma](https://www.alma.careers)** ([code](https://github.com/Dremix10/WarmIntro)) — AI recruiting-outreach agent for investment banking: sources and verifies bankers, drafts and fact-checks personalized cold emails, tracks the funnel end-to-end. A small team of specialized Claude agents (Researcher, Correspondent, Critic, Watcher, Curator) behind a deterministic planner — with two real self-learning loops, not just an LLM wrapper. One is fully closed: a weekly job recalibrates banker/opener/group scoring weights from actual reply and referral outcomes, and the new weights feed straight back into the next targeting run with no human gate. The other is a statistical self-audit: the system checks whether its own Critic's 4-axis review score (specificity, voice match, guardrails, shared ground) actually predicts real replies, computing a Pearson correlation per axis against outcomes.
- **[Tichu](https://aegist.dev)** ([code](https://github.com/Dremix10/cyprus)) — real-time multiplayer card game: Node/Express/Socket.IO backend, React/Vite frontend, an Information-Set Monte Carlo Tree Search AI opponent. Self-hosted via Docker and Nginx.
- **[DOBI](https://www.bookwithdobi.com/chat/cv-sample)** ([code](https://github.com/Dremix10/agent-jones)) — AI booking assistant: qualifies leads and books appointments through a Claude-driven conversation state machine, with structured JSON action-contract output and a fallback parser for malformed model responses; availability comes from a YAML knowledge base, never a model guess. Grew out of the linked open hackathon prototype; DOBI itself runs closed-source for paying clients.
- **[Doom](https://nudge.aegist.dev)** ([code](https://github.com/Dremix10/Doom)) — screen-time nudge agent, built in 3 days at HackRice. Learns normal usage, steps in only when a session is genuinely unusual.

## Competitive programming

- **IOI:** 1× Bronze Medal, 2× Honourable Mention ([results](https://stats.ioinformatics.org/results/CYP)) · Deputy Leader, Cyprus delegation, 2025
- **BOI:** 2× Bronze Medal, 1× Honourable Mention
- **ICPC:** North American Championship 2025, representing Rice
- **Codeforces:** Master, max rating 2266 ([profile](https://codeforces.com/profile/Dremix10)) · co-authored a round with 19,000 participants
- Cyprus Informatics National Team, 2019–2023

## Stack

- **Languages:** C++, Python, JavaScript/TypeScript
- **Frameworks:** React, Next.js, Node.js/Express, Claude API (Anthropic SDK)
- **Infrastructure:** Vercel, Docker, Nginx, GitHub Actions CI
- **Databases:** PostgreSQL (Supabase), SQLite

## Contact

[LinkedIn](https://linkedin.com/in/demetris-chrysostomou-10052004) · dc118@rice.edu · [growzonecy.com](https://growzonecy.com)
