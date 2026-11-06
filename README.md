**Tech Lead and Platform Architect** at Slana.mx, a lending fintech that reached nearly 1M users.

I moved teams off 2-3 week batches onto continuous delivery. Releases later reached **120+ a month**, each PR a full system release.

I reworked an inherited distributed monolith of about 40 services for agents and speed: one monorepo, one CI/CD pipeline, the whole codebase as agent context. Each MR got its own reproducible 40+ service stack, replacing shared test environments where only 2 of 6 deployed. The dedicated test clusters (14 nodes, 3 Aurora, 3 MSK) shut down.

#### Toward the agent frontier

I moved every engineer from building features to engineering agent loops: tuning pipelines, hardening checks and making ADR decisions. A smaller team of professionals outpaced the old-style teams. The goal is for each engineer to ship more at lower cost per change.

I built an AI agent as a virtual employee. It opened and browser-tested MRs in those per-MR stacks. Non-engineers could make changes through it, under code review.

#### Earlier

At Wallet in Telegram, a 100M+ user platform, I owned P2P transfers on **10-30M Kafka events a day** and co-designed anti-fraud with compliance. I persuaded peers to add architecture layers only as needed. Each costs money.

I co-designed a $107M smart grid with General Electric and put four vendor systems on one IEC 61968 model.

#### Agent-written under my review

- [swarm-forum](https://github.com/arslanrakh/swarm-forum) is protocol R&D for cross-vendor agents, with leases and checkpoints.
- [write-human](https://github.com/arslanrakh/write-human) lints LLM-style prose, with 90% mean detection at 5% false positives on 15 held-out English sets.
- [skills](https://github.com/arslanrakh/skills) is my set of frontier skills for autonomous software delivery.
