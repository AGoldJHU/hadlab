# Website Content Updates: Summary for Gilliam

**Prepared by Drew Gold | June 2026**

---

## Page Goals and Intended Audiences

When we redesigned the site in early 2026, we organized each page around a specific goal and audience. Here is a recap of those commitments, which have guided all subsequent updates:

| Page | Goal | Primary Audiences |
|------|------|-------------------|
| **Homepage** | Lead with ideas and positioning, not credentials. The hero text declares what you do; credentials follow. Signals thought leadership across sectors. | Academic peers, policymakers, journalists, general public discovering your work for the first time |
| **Research** | Organize your work around research *questions* rather than findings, grouped into three priority themes: Normative AI, Multi-Agent Systems, and AI Governance. | Academic collaborators, graduate students, funders, peer reviewers |
| **Publications** | A curated, editorially judged selection organized by research theme — deliberately not comprehensive. Venue badges (Science, Nature, PNAS) signal impact at a glance. | Researchers, students, tenure/promotion committees, journalists seeking primary sources |
| **Talks** | Card-based showcase of selected video talks with descriptions and direct links. Links to the full YouTube playlist for completeness. | Conference organizers, prospective students, media bookers, general audience |
| **Media** | Chronological record of press coverage, podcasts, and interviews. Reinforces public intellectual positioning. | Journalists, media bookers, communications offices, general public |
| **Bio** | Narrative-first biography that frontloads current research focus, then follows standard academic structure. CV download available. | Event organizers needing a bio, journalists, prospective collaborators |
| **Normativity Lab** | Full team roster with headshots, organized by role (PI, Research Scientists, Doctoral Students, Undergrads, Staff), alphabetized within each role. Links to personal and professional profiles. | Prospective lab members, collaborators, university administration |
| **Policy** | Highlights testimony and policy engagement across core focus areas (Regulatory Markets, AI Registration & Transparency, International Coordination). Selected policy publications. | Policymakers, government staff, think tanks, policy journalists |

---

## Changes Made Since the Original Launch

The table below lists every page we have updated and the rationale behind each change. Pages not listed (Research, Publications) have not been modified.

### Homepage (index.html)

| Change | Rationale |
|--------|-----------|
| Added reference to the Independent Verification Organization (IVO) model in the "Current Focus" text | Your regulatory-markets research has a concrete legislative instantiation now — the IVO model is being introduced in state and federal legislation, and the homepage should reflect this real-world impact |
| Added a "Research Band" section with three focus-area cards (Normativity and AI Alignment, Cooperative AI, AI Governance) | Gives first-time visitors a quick visual map of your three research pillars without scrolling to the Research page |
| Replaced the sidebar research-themes list with an "Upcoming" section featuring current conferences and events (Workshop on Multi-Agent Ecosystems, AGI Governance Fellowship, The Curve 2026) | The homepage should feel current. Static research themes were already covered by the new Research Band; replacing them with live upcoming events signals active engagement |
| Updated Endgame podcast link from Linkfire URL to direct Apple Podcasts URL | The original aggregator link was unreliable; a direct platform link ensures visitors can actually listen |

### Bio (bio.html)

| Change | Rationale |
|--------|-----------|
| Added "Visiting Faculty Researcher (part-time) in the Paradigms of Intelligence (Pi) Group at Google" to both the intro section and the main biography paragraph | Reflects a new appointment. This affiliation is relevant to your positioning at the intersection of academic research and industry, and visitors — especially media and event organizers — need to see current roles |

### Media (media.html)

| Change | Rationale |
|--------|-----------|
| Merged the separate "Podcasts & Interviews" and "Press Coverage" sections into a single chronological list organized by year (2026, 2025, 2024, ...) | The original category-based split forced visitors to check two sections to see your most recent media. A unified chronological view makes it immediately clear how active and current your public engagement is |
| Updated table-of-contents navigation from category links to year-based links | Matches the new chronological structure and lets visitors jump directly to a specific time period |
| Added new 2026 media entries | Keeps the page current with this year's coverage |

### Normativity Lab (normativity-lab.html)

| Change | Rationale |
|--------|-----------|
| Added Navya Mehrotra as Research Intern (BDP Summer Program) with headshot and profile links | New team member joining the lab |
| Corrected email addresses from @jh.edu to @jhu.edu for multiple team members | Accuracy fix — the original addresses were typos that would have bounced |
| Updated and expanded social/professional links for team members (Google Scholar, GitHub, X/Twitter, LinkedIn, Bluesky) | Makes it easier for collaborators and prospective students to find and connect with lab members through their preferred platforms |
| Corrected Maria Ryskina's Bluesky handle from "maryryskina" to "mryskina" | Accuracy fix |
| Removed redundant "The Normativity Lab Team" header text | Cleaned up a layout redundancy — the page title already establishes this |
| Added CHAI workshop group photo | Documents the lab's participation and community engagement; adds visual warmth to the page |

### Policy (policy.html)

| Change | Rationale |
|--------|-----------|
| Added a featured publication card for "Regulatory Markets: The Future of AI Governance" with descriptive text and co-author credit (Jack Clark) | The regulatory-markets framework is the centerpiece of your policy work. Giving it a prominent visual card — rather than just a list entry — signals its importance to policymakers visiting this page |
| Updated the publication link from a local PDF to the American Bar Association's Jurimetrics publication URL | Links to the authoritative published version rather than a working copy; more credible for a policy audience and ensures the link remains stable |
| Updated regulatory markets paragraph to reference the Great American AI Act | Reflects the latest legislative development connected to your work |

### Talks (talks.html)

| Change | Rationale |
|--------|-----------|
| Added 2026 talk: "AI Regulatory Capacity with Independent Verification Organizations" (FAR.AI Alignment Workshop, March 2026) | Keeps the talks page current with the most recent presentation |
| Enhanced descriptions for all existing talks | The original descriptions were minimal. Fuller descriptions help conference organizers and media bookers understand the substance and relevance of each talk |
| Added a central link to the full YouTube playlist | Visitors who want to browse beyond the curated selection can find everything in one click |

---

## Our Process for Keeping the Site Fresh

Maintaining a website for someone as active as you requires a reliable process — not just a one-time redesign. Here is the approach we follow:

**Event-driven updates.** When something notable happens — a new publication, media appearance, talk, team member, or appointment — we update the relevant page promptly rather than batching changes for a future overhaul. This keeps the site feeling current, which matters especially for the homepage and media page where recency signals active engagement.

**Periodic content reviews.** On a regular cadence, we review the full site to check for:
- Outdated events in the "Upcoming" section of the homepage
- Broken or redirected links (podcast URLs, publication links, team member profiles)
- New team members or departures on the Normativity Lab page
- Accuracy of titles, affiliations, and contact information

**AI-assisted workflow.** We use an AI-assisted development workflow (Claude Code) to make updates efficiently and with version control. Every change is committed to a git repository with a clear description, giving us a full audit trail of what changed and when. This means updates that might otherwise take hours of manual HTML editing — like restructuring the media page or adding a new team member with properly formatted links — can be done quickly and accurately, lowering the barrier to keeping the site current.

**Quality checks.** Before any update goes live, we verify that links work, formatting is consistent across pages, and new content matches the editorial tone established in the redesign.

---

*This document covers all content changes made to the site between the original launch and June 2026. For questions or to request additional updates, contact Drew Gold at ajgold@jhu.edu.*
