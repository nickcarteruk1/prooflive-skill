# Prooflive.ai agent skill

Build a business website with your own AI agent and put it live with [Prooflive.ai](https://prooflive.ai?utm_source=github&utm_medium=skill): real HTML pages on your own domain, hosted in London, with SSL, email on your domain, an enquiries inbox, a blog and search set up automatically. Free to build and preview; from £19 a month when it goes live.

Works with Claude Code, Codex, Cursor, Gemini CLI, GitHub Copilot and Windsurf.

## Install

Any agent that supports skills:

```bash
npx skills add nickcarteruk1/prooflive-skill
```

Claude Code:

```
/plugin marketplace add nickcarteruk1/prooflive-skill
/plugin install prooflive@prooflive
```

Gemini CLI:

```bash
gemini extensions install https://github.com/nickcarteruk1/prooflive-skill
```

## Use

Ask your agent: "Build my business a website with Prooflive". It will ask you to sign up free at [app.prooflive.ai](https://app.prooflive.ai/signup?utm_source=github&utm_medium=skill) and paste your build link, then follow the site's own instructions to ask about your business and build every page.

## Data

The skill tells your agent to send the website it builds (pages, images and the business details you give it, such as name, address and phone) to the Prooflive.ai build API at app.prooflive.ai, using the build link you create in your account. Prooflive.ai stores it to host your site for as long as your account and site exist. See the [privacy policy](https://prooflive.ai/privacy) and [terms](https://prooflive.ai/terms).

## Licence

MIT
