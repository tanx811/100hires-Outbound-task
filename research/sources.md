# Sources — Cold Outreach Pipeline for B2B SaaS

10 practitioners who run cold outreach (cold email, LinkedIn outreach, and cold calling) for a living — as agency founders, in-house sales leaders, or SDR coaches — and publish what they're actually doing, not just commentary. All links verified live as of 2026-06-16.

| # | Name | Role / Proof of practice | Primary channel | Profile / Channel | Date last checked |
|---|------|---------------------------|------------------|--------------------|--------------------|
| 1 | Josh Braun | Runs Josh Braun Sales Training; coaches SDR teams on live cold call/cold email rewrites | LinkedIn (weekly posts) | https://www.linkedin.com/in/josh-braun/ | 2026-06-16 |
| 2 | Alex Berman | Founder of Experiment27 & Galadon; built and exited 5 SaaS companies via cold email; author, *The Cold Email Manifesto* | YouTube (100K+ subs) | https://www.youtube.com/channel/UCAr7M4Pz-c1WCpIz3YAJQeQ | 2026-06-16 |
| 3 | Jack Reamer | CEO of SalesBread, a LinkedIn/cold-email lead-gen agency; 1M+ LinkedIn messages sent, ~20% reply rate across 5 years | LinkedIn + SalesBread blog + Cold Outreach Podcast (co-host) | https://www.linkedin.com/in/jackreamer/ | 2026-06-16 |
| 4 | Morgan J Ingram | Founder/CEO of AMP Social; ex-JBarrows trainer; created The SDR Chronicles after building $30M+ pipeline as a practicing SDR | YouTube (The SDR Chronicles) + LinkedIn | https://www.youtube.com/channel/UCnhg__lkPcrdr2zqLu5kwUQ | 2026-06-16 |
| 5 | Sam Dunning | Founder of Breaking B2B, an SEO/outbound lead-gen agency scaled to $230K+/mo; hosts weekly podcast on what's actually converting | Podcast (Breaking B2B) + blog | https://www.breakingb2b.com/ | 2026-06-16 |
| 6 | Will Aitken | Sales trainer/keynote speaker, co-host of "Sell Better"; built audience from cold outreach experiments documented in public | LinkedIn + YouTube | https://www.linkedin.com/in/justwillaitken/ | 2026-06-16 |
| 7 | Florin Tatulea | Outbound GTM consultant for early-stage B2B SaaS; 9 years as a practicing SDR/AE across 3 companies before consulting | LinkedIn | https://www.linkedin.com/in/florintatulea/ | 2026-06-16 |
| 8 | Leslie Venetz | Founder, The Sales-Led GTM Agency; personally made 250,000+ cold calls before building her outbound training practice | LinkedIn + agency blog | https://www.linkedin.com/in/leslievenetz | 2026-06-16 |
| 9 | Nick Cegelski & Armand Farrokh | Co-hosts of 30 Minutes to President's Club (#1 sales podcast); built 30MPC's own outbound motion to grow the show/courses | Podcast + YouTube breakdowns | https://www.30mpc.com/ | 2026-06-16 |
| 10 | Patrick Dang | Founder of Sales Legacy; ex-Oracle enterprise rep; trained 70,000+ students on cold email/LinkedIn/cold calling he uses himself | YouTube + LinkedIn articles | https://www.youtube.com/channel/UCLOzkJ9W9fntCGyYfUwMPew | 2026-06-16 |

## Why these 10

All ten run outbound as their day job (agency, in-house quota, or training built from their own pipeline), not as theorists repackaging other people's frameworks. They cover the three channels that make up a real cold outreach pipeline — cold email (Berman, Dang, Braun), LinkedIn outreach (Reamer, Tatulea, Aitken), and cold calling (Venetz, Cegelski/Farrokh) — plus one (Dunning) who is candid about where cold outreach is *failing* in 2026, which is necessary signal for a balanced playbook.

## Known limitation: YouTube transcripts

YouTube's caption/transcript endpoints (`timedtext` API, `yt-dlp`, `youtube-transcript-api`) all returned HTTP 429 ("unusual traffic") from this environment's network — Google is blocking automated transcript requests at the IP level, not from per-video restrictions. This was verified with three independent methods (see commit history). Where a creator's primary channel is YouTube, `research/youtube-transcripts/` instead contains the video reference (title, URL, upload context) plus the creator's own written breakdown of the same material (blog post, podcast show notes, or LinkedIn article) as a text-accurate substitute. Pulling true verbatim captions once outside this sandboxed network (e.g., via a Supadata API key, which needs a sign-up the agent can't do unattended) is a clear next step before building the full playbook.
