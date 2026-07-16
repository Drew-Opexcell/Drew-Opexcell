# Drew Patterson

I build automation systems that run real operations: legal intake, document pipelines,
outbound infrastructure, and the monitoring that keeps it all honest. Founder of
[Opexcell](https://opexcell.com), an AI-automation agency for law firms and medical
practices. The flagship engagement runs about 160 production automations (~38,900 runs a
month) for a disability law firm.

I also publish research on the industry I automate for. **The Judge Lottery** (2026)
analyzed 317,462 Social Security hearing decisions and found that judges in the same
hearing office allow claims at rates that commonly differ by more than 30 percentage
points. DOI: [10.5281/zenodo.21392342](https://doi.org/10.5281/zenodo.21392342).

## Live things I've built

- **[Meridian Mailroom](https://meridian-mailroom.vercel.app)** ([source](https://github.com/Drew-Opexcell/meridian-mailroom)): an AI mail-triage pipeline for a disability law firm. Classify, extract, fuzzy-match to a client, route, with a human-review gate for high-stakes letters. A public, synthetic-data demo of the kind of system I build for real firms. Next.js, Claude, live pipeline.
- **[Torchlit](https://torchlit.app)**: an AI dungeon master where a deterministic rules engine owns the world state and the model only narrates. Full app with auth and billing. Next.js, Supabase, Claude.
- **[Parlita](https://parlita.com)**: an AI language-learning partner for the B1-to-C plateau. Voice and text conversation, story role-play, spaced repetition. Next.js, Supabase, tiered Claude + OpenAI, TTS.

## Open source

- **[pebble-lang](https://github.com/Drew-Opexcell/pebble-lang)** ([live playground](https://pebble-lang.vercel.app)): a small scripting language built from scratch in TypeScript. Hand-written lexer, Pratt parser, tree-walking evaluator with real closures. No parser generators, no eval, no deps.
- **[judge-lottery](https://github.com/Drew-Opexcell/judge-lottery)**: the study above, fully reproducible from SSA public data.
- **[jobscout](https://github.com/Drew-Opexcell/jobscout)**: source remote job postings, score them against your target roles, find the hiring manager.
- **[auto-video-editor](https://github.com/Drew-Opexcell/auto-video-editor)**: CLI editor for talking-head video, Silero-VAD silence removal + audio normalization + mistake cutting. Python + FFmpeg.
- **[hushbeat](https://github.com/Drew-Opexcell/hushbeat)**: monitoring that only speaks when something is wrong.

Stack: Python, TypeScript, browser automation (Playwright/CDP), LLM pipelines with human
review gates, and whatever API the job requires.

Contact: drew@opexcell.com · ORCID [0009-0005-9551-4948](https://orcid.org/0009-0005-9551-4948)
