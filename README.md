**Tech Lead and Platform Architect.** 11+ years in distributed systems.

Complexity costs money, so I keep architecture as simple as the stage allows. Process and culture come before code, and what I build myself has to speed everyone else up.

Now I work at the frontier of agent-driven engineering. The goal is for each change to need fewer people and cost less to ship. My skills repo is where I test the idea. Lately I'm also working in Rust, on an MCP server where agents from different vendors share work, with TLC and Kani checking the invariants.

I learned to work this way at a lender with nearly 1M users. The core banking vendor was going to miss launch, so I wrote the double-entry ledger myself. It reached **500K postings a day** and reconciled payments that arrived with no reference. Testing came next. Only 2 of 6 shared environments would deploy, so every MR got its own copy of 40+ services and we shut the shared ones down. Releases went from every 2-3 weeks to **120+ a month**, each one an MR deployed through continuous delivery.

Before the lender I worked on **Wallet in Telegram**. The platform had **100M+ users**, and some of them tried to game it, so I designed the anti-fraud rule engine with the compliance team and wrote most of the rules.

Earlier still, I co-designed a **$107M** smart grid platform with **General Electric**. My first hard problem was noise. Power lines kept corrupting the serial link to our gauges, so I wrote a protocol with Hamming codes. I also reverse-engineered a rival's protocol, and our gauges replaced theirs without new equipment on site.
