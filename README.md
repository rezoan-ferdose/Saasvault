# The 30-Grid

A 30-slot launch plan for indie SaaS. Copy [30-grid-template.md](30-grid-template.md), fill it in, and stop guessing whether a link you posted did anything.

Also here: [profile-README.md](profile-README.md) (the GitHub link slot itself) and [publish-checklist.md](publish-checklist.md) (repo fields, topics, licence, and what to measure two weeks later).

Built and used by [SaaSVault](https://saasvault.pro) — a curated AI tool directory where every listing is a full product page, read by a person before it goes live.

This file lives at [github.com/rezoan-ferdose/Saasvault](https://github.com/rezoan-ferdose/Saasvault). It is documentation only — the directory itself is the site at [saasvault.pro](https://saasvault.pro), and its source is not published here.

## The problem

Founders are told to "go get backlinks". Two things go wrong:

1. **Most of the places you are allowed to post do not pass authority.** Reddit, X, LinkedIn, Medium, Hacker News, Indie Hackers — the outbound links are `nofollow` or `ugc`. You will not gain PageRank from them.
2. **Posting links does not make Google crawl you faster.** Crawl frequency follows crawl demand: does this page change, do people want it. A link on a dead forum page teaches Google nothing.

Both are still worth doing, for a different reason. Since 2019 Google treats `nofollow` as a hint and **follows those links to discover URLs**. So a link on a page Googlebot visits every few minutes genuinely gets *that URL* seen sooner. It buys discovery and readers, not authority.

The grid is organised around that distinction. Every slot has a job. Do not expect a different one.

## The four blocks

| Block | Slots | Job | What success looks like |
|---|---|---|---|
| A. Home base | 1–6 | Pages Googlebot already visits often, on sites you control | New posts discovered within hours, not days |
| B. Launch boards | 7–14 | One-time submissions with real audiences | Referral signups, brand searches |
| C. Written elsewhere | 15–22 | Native articles on high-crawl publishing platforms | Readers, citations, AI engines seeing the name |
| D. Recurring | 23–30 | Things you repeat weekly and never automate | Compound: mentions, reviews, invited links |

Fill the template in order. A blank slot is fine; a spam-filled slot is worse than blank.

The template carries a fifth block — **E, the two levers that beat the other thirty**. It is short, free, and the reason the other slots work at all. Do it before you chase a directory.

## What each surface actually gives you

Verified against the platforms' own behaviour, not against SEO blogs:

| Surface | Link rel | Crawl frequency | Honest verdict |
|---|---|---|---|
| GitHub (profile URL, README) | followed | very high | Best free discovery surface. A repo with real content earns stars too |
| Hacker News (Show HN) | nofollow | extreme | Discovery plus a genuine traffic spike if the post holds up |
| X / LinkedIn / Bluesky | nofollow | high | Discovery and brand searches. No ranking value |
| Medium | nofollow | high | Readers. Also blocks `GPTBot`, `ClaudeBot`, `Bytespider`, `Amazonbot`, `Applebot-Extended`, `GoogleOther` and `meta-externalagent` site-wide, so AI training crawlers cannot read it |
| dev.to / Hashnode | mostly followed | high | Real value, and both accept a canonical URL for syndicated pieces |
| Reddit | nofollow / ugc | high | Traffic and citations when you participate as a person. Link-dropping gets the account removed |
| Product Hunt | nofollow | high | Launch-day traffic, badge people put on their sites |
| Indie Hackers | nofollow | medium | Small, but a real audience of builders |
| Other directories and "dofollow packs" | varies | low | Skip. Google's own spam policy names directory links as a tactic, and mass-submission is the fastest way to look like spam |

## Rules for the grid

1. **One contextual link per article.** Not a wall of links, not a signature link.
2. **Syndicate with a canonical.** When you republish your own piece, set the canonical to the original URL on your site. Otherwise you are competing with yourself.
3. **Never buy links, never use a submission service.** Paid links are the category Google demotes rather than ignores.
4. **Never re-register somewhere you were suspended.** Ban evasion usually costs you the domain's reputation on that platform permanently.
5. **Track the thing that moved.** If a placement sent no visitors and produced no brand searches after two weeks, do not do it again.

## The part that is not about links

Two levers beat every submission combined, and both are free:

- **A feed and a sitemap that agree.** Google reads `sitemap.xml` for `lastmod` and a feed for freshness. If your site has no RSS/Atom feed, you are leaving the cheapest discovery signal on the table.
- **Search Console.** After publishing, URL Inspection → Request Indexing on the 10–20 pages that changed. IndexNow is worth doing too, but it serves Bing, Yandex, Seznam and Naver — never Google.

## Listing on SaaSVault

The reason this file exists in public: we run a directory that refuses to sell placement.

- **A page, not a row.** Every listing gets a written product page — what it does, who it is for, what it costs — filed in a niche room.
- **A person reads it before it goes live.**
- **No position is for sale.** The single featured frame is labelled as sponsorship. Rotating off the front wall changes nothing about your page: same URL, same room, still indexable, still linkable.
- **The verified badge is earned, not paid.** You put a link back to your own listing on your site; we check it daily. Skip it and the listing still stays live.
- **Free to list.** Submit at [saasvault.pro/founder/submit](https://saasvault.pro/founder/submit).

Every page above is server-rendered, edge-cached, and present in the sitemap and in `llms.txt` — so answer engines can read the same HTML a person does.

## Using this grid

1. Copy `30-grid-template.md` into your own repo or Notion.
2. Fill block A this week — it is the only block that is entirely under your control.
3. Work B and C slowly. One honest placement per week beats ten copy-pasted ones.
4. Re-read the table before adding a new channel and ask what job it is doing.

## License

Text is CC BY 4.0 — copy it, remix it, attribution appreciated but not required. Code and product names belong to their owners.

Questions, or a listing you think we should have read: use the contact route on [saasvault.pro](https://saasvault.pro/about).
