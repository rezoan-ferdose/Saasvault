# Publish checklist — the repo itself

Everything to set once, before the README matters. Each item is a field in GitHub's UI,
not a code change.

## 1. Repo setup

| Field | Value | Why |
|---|---|---|
| Repo name | `Saasvault` | the brand repo; the post inside it is The 30-Grid |
| Repo URL | `https://github.com/rezoan-ferdose/Saasvault` | the address every other placement points at |
| Description (About) | `A 30-slot launch plan for indie SaaS. Which links Google follows, which it does not, and what actually makes you crawlable.` | appears in GitHub search and on the social card |
| Website field | `https://saasvault.pro` | this is the followed link — one, not five |
| Topics | `saas`, `indie-hackers`, `startup`, `seo`, `launch-checklist`, `marketing`, `founder` | topics are how GitHub's own discovery surfaces a repo; 5–7 beats 20 |
| Social preview image | upload a 1200×630 image | About → Edit → Social preview. Without it, shared links render as plain text |
| Readme | this folder's `README.md`, on the default branch | |

## 2. Group the files so the repo is readable

```
Saasvault/
├── README.md              ← the post itself
├── 30-grid-template.md    ← what people copy
├── profile-README.md      ← the GitHub profile link slot
├── publish-checklist.md   ← this file
└── LICENSE                ← CC BY 4.0 for the text
```

Do not add a build step, a framework, or a `package.json`. A repo that is four markdown
files and a licence is the kind of thing people star.

## 3. Issue hygiene

- Enable **Discussions** if you will answer them; otherwise leave issues on and reply by email.
- Fill in `ISSUE_TEMPLATE.md` with one line: "What did you fill in, and what happened?"
- Do not enable Projects, Wikis, or Insights for a repo this size.

## 4. License

The README says CC BY 4.0, so `LICENSE` has to say so too. GitHub's licence picker does not
offer Creative Commons for code, so the file carries CC's own attribution notice plus the
link to the canonical 4.0 legal code, and the README states that the licence covers the text,
not the product names. That is enough to be unambiguous; the full legal code lives at
[creativecommons.org/licenses/by/4.0/legalcode](https://creativecommons.org/licenses/by/4.0/legalcode).

## 5. After publishing — the discovery steps

In order, because the order is the point:

1. Add the repo URL to your GitHub **profile README** (`<username>/<username>.md`) — see `profile-README.md`.
2. Add the repo URL to your **profile Website field** if it is your main project.
3. Link the repo from **your own site** — a footer or a `/open-source` page. A link only helps discovery if the page it sits on is crawled.
4. **Search Console → URL Inspection → Request Indexing** on your site's page for the repo. This is the only explicit crawl request Google offers; GitHub does not have one.
5. Confirm your `sitemap.xml` `lastmod` and RSS `pubDate` agree for every URL. IndexNow is worth submitting too, but it serves Bing, Yandex, Seznam and Naver — never Google.
6. Post to Hacker News or Product Hunt **only if the repo is genuinely new to that audience**. One contextual link, then stay in the thread.

## 6. What to measure, and when

Two weeks after each placement. Nothing sooner — nothing is readable sooner.

| Signal | Where | Pass |
|---|---|---|
| Referral sessions from that domain | analytics → referrers | more than zero, repeated across days |
| Brand searches | Search Console → Queries, filtered on your name | impressions rising |
| Repo stars / forks | GitHub → Insights | weak signal, but it is the one GitHub gives you |
| Indexed URLs | Search Console → Pages → Indexed, non-canonical | the count moves |

If a placement produces no referral sessions and no brand searches in two weeks, mark it
`dropped` in `30-grid-template.md`. That is the whole point of writing it down.
