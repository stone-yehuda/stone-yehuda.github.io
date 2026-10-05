# Notes for Claude: Yehuda's personal site

This repo is Yehuda's personal site, served by GitHub Pages at https://stone-yehuda.github.io.
The whole site is one file, `index.html`, with no build step. A push to `main` deploys it in
about a minute.

## Work sections: keep them high level

Yehuda's call (2026-10-05): the work content stays high level so nothing Zello-specific leaks.
Section `01 / WHAT I BUILD` (`id="work"`) was rewritten on that basis. Describe the kind of
work (outbound agents, call-to-CRM upkeep, data models and dashboards, sending setup, evals),
not how Zello wires it together.

- No internal project or agent names, no internal tool names, no vendor-to-workflow mapping.
- No numbers or results unless he gives them to you and says they're fine to publish.
- General tool names are fine in the `04 / STACK` list and hero meta line, the way they'd
  appear on a resume.

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
