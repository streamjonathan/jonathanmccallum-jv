# AGENTS.md — jonathanmccallum-jv (Javanese mirror of jonathanmccallum.com)

Javanese mirror site. Same theme and design as the main site (Paper Light),
content translated into Javanese, meaning-first. Repo: streamjonathan/jonathanmccallum-jv.
Live (when approved): jv.jonathanmccallum.com. Proof: jonathanmccallum-jv.pages.dev.

## Mission

Mirror jonathanmccallum.com in Javanese — every article translated for meaning,
not word for word, in Jonathan's voice: plain short sentences, friendly, positive,
never preachy. An average person interested in Jesus, not an expert or theologian.

## Roles

- **Bobby (Muse) is the lead builder.** He coordinates, builds, pushes to GitHub
  and deploys to Cloudflare. He is the ONLY one who pushes or deploys.
- **Claude advises and reviews** translation quality. He does not push or deploy.
- **Helper Muses translate** one article at a time, drafts only.

## The one rule above all

**Never publish or alter live production assets without Jonathan's clear
permission.** The Javanese site goes live on jv.jonathanmccallum.com only when
he says so, after reading the pilot article(s). Drafts stay drafts until he
approves them. Work on a branch, never straight on main. Give Bobby a preview URL.

## Translation rules

- English repo (streamjonathan.github.io) is the source of truth. Articles are
  translated from the English Markdown, keeping the same date, slug, source_video
  and shareImage. Only the title and body are translated.
- Register: plain everyday ngoko, Latin script throughout. First person "aku",
  reader "kowe" (never "sampeyan"/kromo). Short sentences, warm, honest, no
  preaching. God is "Gusti Allah" throughout; third-person pronoun for God is
  "Dheweke". FLAGS for Jonathan: ngoko "kowe" to an unknown reader can feel very
  familiar — "sampeyan" would change every article; "Panjenengane" is the more
  reverent pronoun for God used in some Javanese Christian writing.
- Names (never vary): Aslan, Narnia, Lucy, Digory, Tirian, Cair Paravel, Adam lan
  Hawa, Petrus (standard Javanese Bible form), Tukang Sihir Putih. Book titles
  stay in English — no published Javanese translation of any Narnia book was
  found. "Surfer" stays the loanword surfer (flagged).
- Bible verses: none of the 5 articles contains a direct Bible quotation, so no
  verse text was reproduced. The bread/water of life lines are Jonathan's
  paraphrase (echoing John 6:35 / 4:14) — roti panguripan / banyu panguripan —
  never presented as quoted Scripture. The standard Javanese Bible is the LAI
  Kitab Sutji (1981; 2006 revision); its public-domain status could not be
  confirmed, so no Kitab Sutji wording is reproduced here.
- No direct Lewis quotations appear either; none were invented.
- No emojis, no newsletter form, no links the English article does not have.
- Never invent facts, dates, links or details.

## Site facts

- Eleventy 3, Cloudflare Pages, Paper Light theme (Fraunces + Newsreader).
- No Ask chat and no note Worker on this site yet — search (Pagefind) works,
  Ask and notes come later. The Ask floating button and ask.js are removed.
- CSS is preloaded, not inlined (CSP blocks inline style). Bump the `?v=` query
  on any CSS/JS file you change.
