# Smart Contracts Architecture & Oracles

The SVM protocol will be composed of multiple modular smart contracts that automate key operations:

#### 🧱 Key Contracts

* **SPT Factory**\
  Deploys new SPTs using bonding curve mechanics, enforces supply caps, and stores athlete metadata.
* **Staking Vaults**\
  Let users deposit SPTs to earn rewards, track weekly performance scores, and handle claim logic.
* **Sporties Ledger**\
  Manages the issuance, accumulation, and redemption of Sporties across social + on-chain actions.
* **Airdrop Allocator**\
  Handles user allocation in each airdrop pool based on Sporties spent and BAG qualification.
* **DAO Governance**\
  Controls protocol parameters, launch approvals, and treasury spending via $SVM-based voting.

All contracts will be upgradeable, auditable, and open for community review.

> SVM is built with modularity in mind — allowing for new components, leagues, and reward types to plug in over time.

***

### 📡 Oracles: Real-World Data → On-Chain Rewards

Staking rewards will be based on **real player performance**, not random math.

#### 🔍 How It Works

* **External sports data providers** feed in match stats (via Chainlink, DIA, oracles like SportMonks, etc.)
* The data is parsed into SVM’s **Performance Formula**, built for each sport
* Scores are assigned to each athlete for that week
* These scores determine the weekly SPT staking reward allocations

No guesswork. No black boxes. Just clean data → clean math → clean yield.

***

### 🔐 Data Sources & Redundancy

* Multiple data providers are integrated to reduce risk of errors or manipulation
* Fallback logic is implemented to handle delays, conflicts, or anomalies
* Key inputs include: goals, assists, minutes played, wins/losses, fantasy points (depending on sport)

Each sport uses its own **performance scoring model**, tuned for fairness and impact.

***

### 📣 Upcoming Tech Enhancements

We’re building toward:

* Gasless claim flows using meta-transactions
* Cross-chain Sporties tracking
* Modular contract support for custom league integrations
* Plugin-based oracle aggregation per sport

> As the protocol grows, so will the tooling — and anyone will be able to build with it.

***

### 🏁 TL;DR

* Smart contracts run all core SVM mechanics — from SPT creation to staking and airdrops
* Oracles bring live match data on-chain to trigger reward distributions
* The system is open, trustless, and designed to scale
* No centralized scorekeeping, no human tweaking — just provable, real-time sportfi logic

**Code is the ref. Data is the judge. You bring the belief.**
