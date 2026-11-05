Tech Lead and Platform Architect. 11+ years in distributed systems.

I started on industrial hardware, with a Hamming-coded RS-485 protocol that survived noise from power lines and a reverse-engineered rival protocol that let our gauges replace theirs without touching the site. Then I co-designed a **$107M** smart grid platform with **General Electric**, unifying 4 vendor systems on one IEC 61968 model and moving 96M grid parameters an hour.

At **Wallet in Telegram**, **100M+ users**, I owned P2P transfers and anti-fraud. I designed the rule engine and the facts store behind it, on 10-30M Kafka events a day.

At a regulated lender with nearly 1M users, I inherited about 40 services and no time. I built a double-entry ledger that reached 500K postings a day and could reconcile payments with no reference. I moved 41 services into one monorepo, with deploys that skip unchanged services. Then every MR got its own environment of 40+ services, and we shut down the shared test clusters. Releases went from every 2-3 weeks to 120+ a month.

After that came specs in Git with gates in CI, Claude Code as the team standard, and agents that rebase and repair open MRs. Lately it's Rust, an MCP server where agents from different vendors share work, with fencing tokens and invariants checked in TLC and Kani.

I keep architecture as simple as the project's stage allows, because complexity is what costs money. Processes and culture come first. What I build myself is what speeds everyone up.
