**Tech Lead and Platform Architect.** 11+ years in distributed systems.

Every extra layer of architecture costs money, so I add one only when the stage needs it. Process and culture come first. Anything I build myself should speed up the whole team.

#### Now, at the frontier of agent-driven engineering

The goal is for each engineer to ship more, at a lower cost per change. My skills repo tests the idea. I also build a Rust MCP server for agents from different vendors to share work. Fencing tokens keep them off each other's slots, and TLC and Kani check the invariants.

#### Slana.mx, regulated lender with nearly 1M users

The core banking vendor was going to miss launch, so I wrote the double-entry ledger myself, up to **500K postings a day**.

- Moved 41 services into one monorepo.
- Took releases from every 2-3 weeks to **120+ a month**.
- Made **Claude Code** the standard and put spec gates in CI.
- Built an AI agent that acted as a virtual employee. Its access covered Slack, GitLab, Jira, Confluence, Sentry, logs and telemetry.
- People messaged it, mentioned it in comments, and assigned it tasks and MRs. It asked questions back, kept memory and coordinated its own parallel work.
- Gave each MR a reproducible environment of 40+ services. The agent used them too, opening an MR, reviewing it and testing the flow in its own browser.

#### Wallet in Telegram, platform with 100M+ users

- Designed the anti-fraud rule engine with the compliance team.
- Owned P2P transfers on 10-30M Kafka events a day.
- A viral launch sent traffic up 10x, and user services had to hold.

#### Orthosnap, part-time, US orthodontic SaaS with 2,000+ clinics

- Cut CI from 40 minutes to 8 by starting test environments on demand.
- Built S3, SQS and Lambda pipelines for remeshing 3D jaw scans, cutting processing costs.

#### Chief Systems Architect at a utility with 4M consumers

- Co-designed a **$107M** smart grid platform with **General Electric**.
- Put 4 vendors on one IEC 61968 model.
- Wrote the integration core for 96M grid parameters an hour.

#### First job, industrial gauge maker

Power lines corrupted our gauges' serial link, so I wrote a protocol with Hamming codes. I also reverse-engineered a rival's protocol, which let our gauges replace theirs with no new equipment.
