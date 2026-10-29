# Lukas Mandrake

Data scientist and AI researcher at NASA's Jet Propulsion Laboratory, where I have worked since 2002. Physicist by training (Ph.D., UCLA), with a career in machine learning for science instruments and autonomy.
My current question is when an AI answer can be checked, and what to do when it cannot.
I build with Claude Code every day. The repositories below are public, open-source work, and each states what was measured and what was not.

## Repositories

- **[Lodestar](https://github.com/Lmandrake/Lodestar)**: an operating layer for running a fleet of AI coding agents across several machines. Its hourly sync sweep never forces, and a deliberately rewritten upstream halts the sweep instead of merging old history back in.
- **[Dispatch](https://github.com/Lmandrake/Dispatch)**: a router that picks the model and agent harness per task from measured results. On LiveCodeBench v6 (175 problems), Haiku with up to 3 tries against the public tests, then Opus, scored 0.84 against Opus alone at 0.82, at 29% of Opus's cost.
- **[Dialexis](https://github.com/Lmandrake/Dialexis)**: a personal knowledge graph in markdown where a model proposes changes and deterministic code refuses any illegal one. The mechanism is tested; whether it prevents errors is stated as not yet measured.
- **[NASA-Guidance-Docs](https://github.com/Lmandrake/NASA-Guidance-Docs)**: a Claude skill that maps NASA's software, safety and mission-assurance governance documents, with a locator on every claim, drawn only from public documents.
- **[EvidenceBoundPapers](https://github.com/Lmandrake/EvidenceBoundPapers)**: a harness for AI-assisted science where every claim traces to evidence and a checker that calls no model enforces it. The example passes 21/21 applicable checks; change one word in a quoted span and it halts at 19/21.
- **[MandrakeWorkflows](https://github.com/Lmandrake/MandrakeWorkflows)**: methods for working with AI agents, written as Claude Code skills. Each says what it rests on, what was measured and where it has not been tested. It also holds Placard, plain markdown digests beside decks, PDFs and spreadsheets so an agent reads them once (on the shipped example, 81% fewer input tokens than native document input with no loss on 14 questions; one small synthetic folder, one model), and a visual-reasoning skill stack whose critic grades figures against 13 honesty gates (evaluated by a 6-case ablation and a 36-case blind bake-off).

Publications: [Google Scholar](https://scholar.google.com/citations?user=ADh_bQgAAAAJ&hl=en).
