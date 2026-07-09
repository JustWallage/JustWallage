# Just Wallage

**Full-stack product engineer building feedback-loop-driven workflows to ship at AI velocity**

I build full-stack systems that work for AI-driven development; the hard part isn't generating code, it's trusting it. That's why I focus on building strict **feedback loops** around the model:

- **Deterministic checks on every commit** — build, typecheck, lint, dead-code (knip), duplication (jscpd), unit test, and E2E tests
- **Independent AI review gates** — spec- and code-reviewer loops, each running in *fresh* context: **[justly-skilled](https://github.com/JustWallage/justly-skilled)**
- **Fully ephemeral E2E stage** — each run provisions its own environment + all resources and tears it down after, tests never touch shared state and can run in parallel
- **Live context documents** — `CLAUDE.md` files per package, explaining ONLY what's hard/expensive for LLMs in that specific package ([example](https://github.com/JustWallage/news/blob/main/iac/CLAUDE.md))

Shipping *fast* only counts if you ship with complete *trust* in the code.

## Some of my projects

- **[JustWallage/news](https://github.com/JustWallage/news)** — live & public AI-curated Hacker News feed ([news.justwallage.nl](https://news.justwallage.nl)) + integrated Telegram updates
- **[justly-skilled](https://github.com/JustWallage/justly-skilled)** — dual review loop workflow for Claude Code
- **[iglympics](https://github.com/JustWallage/iglympics)** — real-time competition dashboard for a 14-friend weekend trip. Shipped new features live during the weekend from my phone, possible because of the guardrails
- **[just-wallage-portfolio](https://github.com/JustWallage/just-wallage-portfolio-v1)** — live on: [just.wallage.nl](https://just.wallage.nl). Monorepo with my public profile and an API showcase, built in four ways — Node/Hono, Bun, and Go on AWS Lambda, and Cloudflare Worker
- **[jaw-finance](https://github.com/JustWallage/jaw-finance)** — personal AI bank transaction insights: _What did I spend on food last month?_. Not public for compliancy reasons.

## More about me

- Portfolio: **[just.wallage.nl](https://just.wallage.nl)**
- LinkedIn: **[linkedin.com/in/justwallage](https://www.linkedin.com/in/justwallage)**
