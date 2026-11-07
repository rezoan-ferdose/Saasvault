# The 30-Grid — fill this in

Copy this file into your own repo. One line per slot. A blank slot is fine; a spam-filled slot is worse than blank.

Rules that apply to every row:

- One contextual link, not a wall of them.
- Republishing your own piece? Set the canonical URL to the original on your site.
- Nothing here makes Google crawl you faster. Links buy **discovery** and **readers**. The crawl-speed levers are in Block E.
- If a slot sent no visitors and no brand searches after two weeks, mark it `dropped` and stop doing it.

**Legend** — Status: `todo` / `done` / `dropped` · Rel: `followed` / `nofollow` / `ugc` / `n/a`

---

## Block A — Home base (slots 1–6)

Pages Googlebot already visits often, on sites you control. Do this block first; it is the only one entirely under your control.

| # | Placement | Rel | Status | URL posted | Notes |
|---|---|---|---|---|---|
| 1 | GitHub profile — Website field | followed | todo | | free, high-crawl, permanent |
| 2 | GitHub repo with real content + README | followed | todo | | a tool, dataset, or template people can actually use |
| 3 | Your own blog index / homepage | n/a | todo | | every new post must be linked from a page that is crawled daily |
| 4 | RSS or Atom feed | n/a | todo | | if you have none, this slot outranks every submission below |
| 5 | `sitemap.xml` `lastmod` correct | n/a | todo | | must reflect real edit dates, not the build date |
| 6 | Search Console: Request Indexing on the 10–20 changed URLs | n/a | todo | | the only explicit "look at this now" button Google gives you |

## Block B — Launch boards (slots 7–14)

One-time submissions with real audiences. Success here is signups and brand searches, not links.

| # | Placement | Rel | Status | URL posted | Notes |
|---|---|---|---|---|---|
| 7 | Hacker News — Show HN | nofollow | todo | | only if it is genuinely new and you stay in the thread |
| 8 | Product Hunt | nofollow | todo | | launch-day traffic plus a badge founders put on their own sites |
| 9 | Indie Hackers | nofollow | todo | | small, real audience of builders |
| 10 | A curated directory in your niche | varies | todo | | pick one a human reads; skip the submission packs |
| 11 | AlternativeTo / a comparison page | varies | todo | | only where your product genuinely belongs |
| 12 | Newsletter that accepts a guest section | n/a | todo | | the audience matters more than the link |
| 13 | Podcast / YouTube creator in the niche | varies | todo | | their description box, not your own |
| 14 | Community you already belong to | varies | todo | | if you have never posted there, this is not a slot |

## Block C — Written elsewhere (slots 15–22)

Native articles on platforms with high crawl frequency. Each one has to be worth reading on its own.

| # | Placement | Rel | Status | Canonical set? | Notes |
|---|---|---|---|---|---|
| 15 | dev.to | mostly followed | todo | yes | supports a canonical URL for syndicated posts |
| 16 | Hashnode | mostly followed | todo | yes | same — canonical to your own URL |
| 17 | Medium | nofollow | todo | yes | readers, but it blocks `GPTBot`, `ClaudeBot`, `Bytespider`, `Amazonbot`, `Applebot-Extended`, `GoogleOther`, `meta-externalagent` — AI training crawlers cannot read it |
| 18 | A guest post on a site in your niche | varies | todo | n/a | one contextual link in the body, not a bio-box wall |
| 19 | Your own deep explainer / how-to | n/a | todo | n/a | the page other slots point at |
| 20 | Answer on a Q&A site where you have history | nofollow | todo | | must be the best answer, not a link with an answer attached |
| 21 | Open-source tool related to your product | followed | todo | | repo link plus a real README |
| 22 | Comparison piece: you vs the incumbent, honestly | n/a | todo | | include what the incumbent does better |

## Block D — Recurring (slots 23–30)

Things you repeat weekly. Never automate these.

| # | Habit | Frequency | Status | Owner | Notes |
|---|---|---|---|---|---|
| 23 | Reply to every mention | weekly | todo | | free, and it is what turns one post into repeat referrals |
| 24 | Update one existing page properly | weekly | todo | | real `lastmod` change beats a new thin post |
| 25 | Collect reviews on a platform buyers check | monthly | todo | | G2 / Capterra / Trustpilot — whichever your buyers actually read |
| 26 | Post the changelog where users are | weekly | todo | | also feeds Block A's freshness signal |
| 27 | Fix one thing the last placement surfaced | weekly | todo | | the reason to do placements at all |
| 28 | Check Search Console: coverage errors + queries | weekly | todo | | watch impressions and brand queries, not just clicks |
| 29 | Refresh one stale article with new numbers | monthly | todo | | recency is a citation gate in AI answers |
| 30 | Ask one person for one link, with context | weekly | todo | | a real request to a real site, not a form email |

## Block E — the two that beat the other thirty

| Lever | Status | Notes |
|---|---|---|
| Feed + sitemap that agree | todo | `lastmod` in the sitemap and `pubDate` in the feed must be the same date for the same URL |
| Search Console + IndexNow | todo | IndexNow covers Bing, Yandex, Seznam and Naver — never Google |

---

## Scorecard

| | Count |
|---|---|
| Slots done | 0 |
| Slots dropped | 0 |
| Referral signups this month | |
| Brand searches this month | |

Two numbers matter and both come from other people's data, not your analytics dashboard:
**referral signups** (which placement produced an account) and **brand searches**
(Search Console queries containing your name). A slot that produces neither for two
weeks is a slot you should have left blank.
