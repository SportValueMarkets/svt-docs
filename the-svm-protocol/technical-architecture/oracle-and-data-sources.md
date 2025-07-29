# Oracle & Data Sources

SVM runs on real-world performance — but that data doesn’t live on-chain by default. This is where the data layer comes in.

The protocol ingests trusted match statistics from a verified off-chain source. Those stats are then processed through the on-chain scoring logic that determines rewards, token yield, and staking outcomes.

It’s not just a feed — it’s the foundation of performance-based value.

***

#### 📡 Why Data Feeds Matter

Smart contracts can’t see what happens in the stadium. But SVM is built on real-world actions:

* Goals
* Assists
* Red cards
* Tackles
* Minutes played

All of these events feed into the scoring engine — which drives staking rewards, airdrop weight, and performance-based bonuses.

Without reliable data, the system doesn’t function. With it, fans don’t just watch matches — they earn from them.

***

#### 🧠 What Gets Tracked

The protocol uses verified match data to generate scoring inputs such as:

* **Match Stats**\
  Goals, assists, clean sheets, minutes played, cards, penalties, etc.
* **Live Event Triggers**\
  Red cards, injury flags, substitution timing, etc.
* **Meta Context**\
  Season-long stats, player availability, recent performance trends

These stats are passed into the scoring matrix defined by the protocol — and applied equally across all staked SPTs for the relevant gameweek.

***

#### 🔒 Trust, Not Guesswork

SVM uses a **centralized but verifiable data source** — not a blockchain oracle network — to supply this data.

> There is no "oracle voting" or feed aggregation. One source, tracked and scored transparently.

All scoring logic is applied consistently, on-chain, using that data. No admin overrides. No manual reward edits. Just a clear path from data → score → reward.

***

#### 🔄 Scoring Cycle

After each match window closes:

1. Match data is pulled from the source
2. Each SPT’s performance is scored based on the current matrix
3. Scores are recorded and fed into staking reward calculations
4. Claim periods begin

Processing is near real-time — but includes time buffers to protect against last-minute data corrections or anomalies.

***

#### 🏗 Designed to Expand

As the ecosystem grows, the data layer is structured to support:

* Additional leagues and sports
* Role-specific scoring (e.g. keepers vs forwards)
* Updated scoring matrices via DAO proposal
* Integration of campaign-based metrics, such as fan voting or off-field events _(if ever verified)_

> The feed might start simple — but it’s designed to handle complexity as the protocol scales.

***

#### 🏁 TL;DR

* Real-world match stats are the fuel behind every staking reward
* One verified data source feeds the protocol — no decentralized oracle layer yet
* Stats are passed through the scoring matrix → into staking and airdrop systems
* Designed for fairness, consistency, and future sport expansion

**Fans create the value. Stats verify it.**\
**SVM turns it all into on-chain rewards.**
