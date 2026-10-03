# Notes for Claude: Yehuda's personal site

This repo is Yehuda's personal site, served by GitHub Pages at https://stone-yehuda.github.io.
The whole site is one file, `index.html`, with no build step. A push to `main` deploys it in
about a minute.

## Why this note exists

The site was redesigned on 2026-10-03 by a Claude session that had his career history but not
the details of his day-to-day GTM work. **The Claude he uses at work has that context**, so
the job of whoever opens this repo next is to make the work sections specific and accurate.

## What to improve

Section `01 / WHAT I BUILD` (`id="work"`) is the priority. The current cards are accurate but
general. Fill them in from what he actually built and runs:

- **Data pipelines & reporting.** How he sets up and manages the pipelines (sources, what moves
  where, the warehouse and dbt layer) and the reporting on top (Omni, Hex, the dashboards people
  actually use).
- **Inboxes & deliverability.** How he sets up and manages multiple sending inboxes, and what he
  does to keep deliverability healthy. Name the real tools and practices. The current tags
  (`multi-inbox`, `deliverability`, `domain health`) are placeholders.
- **Agentic prospecting, call-to-CRM automation, evals & observability.** Swap general phrasing
  for the real workflow: what triggers it, what it writes back, who reviews it.
- **Results.** If he is comfortable sharing any outcome (time saved, volume handled, adoption),
  one real number per card beats any adjective. Ask him before you publish any number.

The diagram in that section (signals → research → draft → human review → CRM write-back) can
change if his real flow looks different.

## Guardrails

- **This repo is public.** Do not put customer names, internal Zello metrics, revenue numbers,
  credentials, or anything under NDA on the page or in this file. Describe the work, not the
  company's data. When unsure, ask him.
- Do not invent tools, titles or results. Everything on the page should be something he can
  talk about in an interview.
- Keep the layout and styling unless he asks for changes. The visual design is settled.

## Write it in his voice

He wants the copy to sound like him, not like an AI. His rules:

- Plain, direct, first person. Say the thing, then stop. Short sentences and short paragraphs.
- Specific beats general. Name the real tool, the real step, the real number.
- **No em dashes, ever.** Use commas, periods or colons instead.
- No slogan-style lines ("X beats Y", "If it isn't X, it isn't Y") and no clever asides.
- No AI-tell words: delve, harness, leverage, seamless, robust, pivotal, tapestry, testament,
  realm, unlock, supercharge, game-changer, "in today's fast-paced world".
- No slashes between alternatives ("available/relevant"). Pick one word.
- Warm and confident, never salesy. A friendly close is fine.

A line he wrote himself, for reference: *"I joined as a Business Data Analyst and gradually
found myself spending more time building AI agents, designing automation workflows, and
connecting LLMs to real business processes. At some point, the old title just stopped being
accurate."*

## Checking your change

Open `index.html` in a browser at desktop width and at phone width (about 390px). The page
must not scroll sideways on a phone. Then push to `main` and confirm the live site updated.
