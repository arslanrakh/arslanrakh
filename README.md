**Tech Lead and Platform Architect.** 11+ years in distributed systems.

Complexity costs money, so I keep architecture as simple as the stage allows. Process and culture come before code, and what I build myself has to speed everyone else up.

Now I work at the frontier of agent-driven engineering. The goal is for each change to need fewer people and cost less to ship. My skills repo is where I test the idea. Lately I'm also working in Rust, on an MCP server where agents from different vendors share work. Fencing tokens keep them off each other's slots, and TLC and Kani check the invariants.

I learned to work this way at a lender with nearly 1M users, about 40 services and a launch date. The core banking vendor was going to miss launch, so I wrote the double-entry ledger myself. It reached **500K postings a day** and reconciled payments that arrived with no reference. I moved 41 services into one monorepo, with deploys that skip unchanged services. Testing came next. Only 2 of 6 shared environments would deploy, so every MR got its own copy of 40+ services and we shut the shared ones down. Releases went from every 2-3 weeks to **120+ a month**, each one an MR deployed through continuous delivery.

Agents changed the work next. Specs got gates in CI, **Claude Code** became the standard, and anyone in the company could ask a Slack agent for a small change. The agent opened an MR for review. Other agents rebased and repaired open MRs.

Before the lender I worked on **Wallet in Telegram**. The platform had **100M+ users**, and some of them tried to game it, so I designed the anti-fraud rule engine with the compliance team and wrote most of the rules. I owned P2P transfers on 10-30M Kafka events a day. A viral launch sent traffic up 10x and the user services had to hold.

On the side I worked on a US orthodontic SaaS that 2,000+ clinics used daily. I cut its CI from 40 minutes to 8 and built S3, SQS and Lambda pipelines for remeshing 3D jaw scans.

Earlier, as Chief Systems Architect at a utility serving 4M consumers, I co-designed a **$107M** smart grid platform with **General Electric**. I put 4 vendors' systems on one IEC 61968 model and wrote the integration core, which moved 96M grid parameters an hour.

Long before that, at an industrial gauge maker, my first hard problem was noise. Power lines kept corrupting the serial link to our gauges, so I wrote a protocol with Hamming codes. I also reverse-engineered a rival's protocol, and our gauges replaced theirs without new equipment on site.
