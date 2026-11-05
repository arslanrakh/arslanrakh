Tech Lead and Platform Architect. 11+ years in distributed systems.

My first hard problem was noise. Power lines kept corrupting the serial link to our gauges, so I wrote a protocol with Hamming codes to get through. Then I reverse-engineered a rival's protocol, and our gauges replaced theirs without new equipment on site.

That road led to the power grid. I co-designed a **$107M** smart grid platform with **General Electric**, got 4 vendors' systems onto one IEC 61968 model, and wrote the integration core that moved 96M grid parameters an hour.

**Wallet in Telegram** had **100M+ users**, and some of them were trying to game it. With the compliance team I designed the anti-fraud rule engine and wrote most of the rules. A viral launch sent traffic up 10x and the user services had to hold.

After that, a lender with nearly 1M users, about 40 services and a launch date. The core banking vendor wasn't going to make it, so I wrote the ledger myself. It reached 500K postings a day and could reconcile payments that arrived with no reference.

Testing was the next wall. Only 2 of 6 shared environments would deploy and merge requests kept piling up, so every MR got its own copy of 40+ services and we shut the clusters down. Releases went from every 2-3 weeks to 120+ a month.

Agents came last. Specs went into Git with gates in CI, Claude Code became the team standard, anyone in the company could ask a Slack agent for a small change, and other agents kept open MRs rebased and repaired.

Lately I'm in Rust, on an MCP server where agents from different vendors share work. Fencing tokens keep them off each other's slots, and TLC and Kani check the invariants.

Complexity is what costs money, so I keep architecture as simple as the stage allows. Process and culture come before code, and what I build myself has to speed everyone else up.
