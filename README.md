# Cold Outreach Pipeline for B2B SaaS — Research

Research base for a future cold outreach playbook (cold email, LinkedIn outreach, and cold calling) for B2B SaaS, built from 10 practitioners who run outbound as their actual job rather than commentators repackaging other people's frameworks.

## Why this topic

Cold outreach is the channel with the most contested, fastest-moving advice in B2B SaaS right now — what worked in 2023 (volume cold email) is explicitly called dead by some of these same practitioners in 2026. That tension makes it a good subject for primary-source research instead of recycled "10 tips" content.

## Why these 10 experts

Every person/duo here satisfies at least one of:
- Runs an agency that delivers outbound as a paid service (Reamer/SalesBread, Dunning/Breaking B2B, Berman/Experiment27)
- Built their content from their own quota-carrying SDR/AE experience (Ingram, Tatulea, Venetz, Aitken)
- Hosts the highest-signal operator-level sales podcast in the space and is transparent about real call/email mechanics (Cegelski & Farrokh / 30MPC)
- Has a long public track record of cold email specifically, with measurable outcomes (Braun, Dang)

Full list with links, roles, and proof-of-practice is in [`research/sources.md`](research/sources.md).

We deliberately included Sam Dunning, who argues cold outreach alone is *underperforming* in 2026 — a real playbook needs the dissenting view, not just cheerleaders.

## What's in here

- [`research/sources.md`](research/sources.md) — all 10 experts: links, roles, dates checked, and why each was picked.
- [`research/linkedin-posts/`](research/linkedin-posts/) — individual LinkedIn posts, fetched and annotated, organized by author. Covers 9 of 10 experts (Sam Dunning's primary channel is podcast/blog, already covered under `other/`).
- [`research/youtube-transcripts/`](research/youtube-transcripts/) — verbatim auto-caption transcripts pulled via [Supadata](https://supadata.ai/) API, organized by creator. Each subfolder contains real transcript `.md` files plus an earlier supplementary-notes file (kept for context). Creators covered: Alex Berman (2 videos), Morgan J Ingram (Lemlist webinar), 30MPC/Nick Cegelski & Armand Farrokh (Sales Development Podcast appearance), Patrick Dang, Will Aitken.
- [`research/other/`](research/other/) — agency blog posts and podcast show notes that didn't fit the LinkedIn/YouTube split but are primary-source material from the same 10 experts.

## How material was collected

- **LinkedIn posts:** fetched directly from public post URLs surfaced via web search, using WebFetch on public post pages.
- **Articles/blog/show notes:** fetched directly from the practitioner's or their agency's own site.
- **YouTube transcripts:** pulled via [Supadata](https://supadata.ai/) transcript API against specific video IDs (auto-captions). Initial attempts via `youtube-transcript-api`, `yt-dlp`, and YouTube's `timedtext` endpoint all returned HTTP 429 from the build environment's shared IP — resolved by switching to Supadata.

## Next steps toward a real playbook

1. Add 2–3 more LinkedIn posts per author to triangulate consistent advice vs. one-off takes.
2. Cross-reference where these 10 agree vs. disagree (e.g., Dang says cold email isn't dead, Dunning says cold outreach is underperforming) and build the playbook around resolving that tension with current data.
3. Pull transcripts for Sam Dunning's Breaking B2B episodes on outbound (podcast, not just blog) to round out his coverage.
