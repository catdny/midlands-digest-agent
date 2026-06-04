# Source list

> This file is your editorial position on whose work to trust, whose to read sceptically, and whose to treat as noise. The agent uses it to weight what it surfaces and to flag confidence levels.
>
> The richer this file, the better the agent's triage. Add to it as you build your beat.

---

## Tier 1 — Trusted

*Sources you treat as reliable on first read. The agent can cite them without strong caveats.*

**Trusted news outlets**
- www.itv.com/news/central
- www.itv.com/news/anglia
- www.bbc.co.uk./news/england
- www.news.sky.com/uk

**Beat reporters (any outlet)**
- Phil Mackie (BBC)
- Navtej Johal (BBC)
- Lisa Dowd (Sky News)
- Shamaan Freeman-Powell (Sky News)
- Shaun Lintern (The Sunday Times) - does lots of work on health scandals
- Michael Buchanan (BBC) - does lots of work on health scandals

**Regional police forces - for breaking news or court cases**
- West Midlands Police
- West Mercia Police
- Warwickshire Police
- Staffordshire Police
- Leicestershire Police
- Nottinghamshire Police
- Derbyshire Police
- Northamptonshire Police
- British Transport Police
- The National Crime Agency

---

## Tier 2 — Read with care

*Sources worth reading but where you check claims independently. Could be partisan, agenda-driven, or just inconsistent. Useful for tip-offs, not for direct citation.*

**Local papers - any outlet**
- Birmingham Mail
- Coventry Telegraph
- The Express & Star
- The Stoke Sentinel
- The Nottingham Post
- The Derby Telegraph
- The Leicester Mercury
- The Tab - good for student based stories, viral trends, gossip

**Local Instagram pages - good for viral videos**
- @imjustbrum
- @brum_life_

**University press releases**
- University of Birmingham
- Aston University
- University of Nottingham
- University of Leicester

---

## Tier 3 — Noise / sceptical

*Sources to discount or ignore. The agent should not surface stories from these unless multiple Tier 1 sources have picked them up.*

- Partisan think tanks running campaigns rather than analysis
- AI-generated content farms

---

## Sources I want monitored daily

*A short list of URLs, RSS feeds, or named writers the agent should always check, in priority order. The daily prompt will use this.*

**Example:**
1. www.bbc.co.uk/news/england
2. www.news.sky.com/uk
3. www.itv.com/news/central
4. www.itv.com/news/anglia
5. https://www.dailymail.com/home/index.html?dm=8a076543-1589-4c30-8b15-2f559033a950
6. https://www.birminghammail.co.uk/
7. https://www.coventrytelegraph.net/
8. https://www.nottinghampost.com/
9. https://www.leicestermercury.co.uk/

---

## How I want sources flagged in output

- Tier 1 sources: cite by name without caveat. *"BBC News reports"*, *"West Midlands Police says*
- Tier 2 sources: cite with attribution context. *"According to the Birmingham Mail"*
- Tier 3 sources: do not cite. If a Tier 3 source is the only one carrying a story, flag it as: *"Currently only reported by [source], not yet picked up by trusted outlets — monitor."*
