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
- West Midlands Police: https://www.westmidlands.police.uk/news/west-midlands/news/
- West Mercia Police: https://www.westmercia.police.uk/news/west-mercia/news/
- Warwickshire Police: https://www.warwickshire.police.uk/news/warwickshire/news/
- Staffordshire Police: https://www.staffordshire.police.uk/news/staffordshire/news/
- Leicestershire Police: https://www.leics.police.uk/news/leicestershire/news/
- Nottinghamshire Police: https://www.nottinghamshire.police.uk/news/nottinghamshire/news/
- Derbyshire Police: https://www.derbyshire.police.uk/news/derbyshire/news/
- Northamptonshire Police: https://www.northants.police.uk/news/northants/news/

---

## Tier 2 — Read with care

*Sources worth reading but where you check claims independently. Could be partisan, agenda-driven, or just inconsistent. Useful for tip-offs, not for direct citation.*

**Local papers - any outlet**
- Birmingham Mail: https://www.birminghammail.co.uk/
- Coventry Telegraph: https://www.coventrytelegraph.net/
- The Express & Star: https://www.expressandstar.com/
- The Stoke Sentinel: https://www.stokesentinel.co.uk/
- The Nottingham Post: https://www.nottinghampost.com/
- The Derby Telegraph: https://www.derbytelegraph.co.uk/
- The Leicester Mercury: https://www.leicestermercury.co.uk/
- The Tab - good for student based stories, viral trends, gossip: https://thetab.com/

**Local Instagram pages - good for viral videos**
- @imjustbrum
- @brum_life_

**University press releases**
- University of Birmingham: https://www.birmingham.ac.uk/news
- Aston University: https://www.aston.ac.uk/latest-news
- University of Nottingham: https://www.nottingham.ac.uk/news/
- University of Leicester: https://le.ac.uk/news

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
10. Daily police sweep - Check all eight force newsrooms listed under Tier 1 for anything involving a death, serious assault, or arrest of a minor/vulnerable person, even if it doesn't relate to an existing thread. Flag anything that could develop into a Top Story or Middle Story.

---

## How I want sources flagged in output

- Tier 1 sources: cite by name without caveat. *"BBC News reports"*, *"West Midlands Police says*
- Tier 2 sources: cite with attribution context. *"According to the Birmingham Mail"*
- Tier 3 sources: do not cite. If a Tier 3 source is the only one carrying a story, flag it as: *"Currently only reported by [source], not yet picked up by trusted outlets — monitor."*
