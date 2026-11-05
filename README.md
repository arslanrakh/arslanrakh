**Tech Lead and Platform Architect.** 11+ years in distributed systems.

My first hard problem was noise. Power lines kept corrupting the serial link to our gauges, so I wrote a protocol with Hamming codes to get through. Later I reverse-engineered a rival's protocol, and our gauges replaced theirs without new equipment on site. That road led to the power grid and a **$107M** smart grid platform I co-designed with **General Electric**.

**Wallet in Telegram** had **100M+ users**, and some of them were trying to game it. With the compliance team I designed the anti-fraud rule engine and wrote most of the rules.

After that, a lender with nearly 1M users, about 40 services and a launch date. The core banking vendor wasn't going to make it, so I wrote the ledger myself, and it reached 500K postings a day. Testing was the next wall. Only 2 of 6 shared environments would deploy, so every MR got its own copy of 40+ services and we shut the clusters down. Releases went from every 2-3 weeks to **120+ a month**.

Agents came last and changed what I work on. Specs got gates in CI, Claude Code became the standard, and anyone in the company could ask a Slack agent for a small change. Now I work at the frontier of this, with each change needing fewer people and costing less to ship. My skills repo is where I test it. Lately I'm also in Rust, on an MCP server where agents from different vendors share work, with TLC and Kani checking the invariants.

Complexity is what costs money, so I keep architecture as simple as the stage allows. Process and culture come before code, and what I build myself has to speed everyone else up.
