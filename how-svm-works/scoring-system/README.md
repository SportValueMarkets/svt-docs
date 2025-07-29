# 🥅 Scoring System

The SVM scoring system is the engine that drives how athlete performance is measured, how staking rewards are distributed, and how users engage strategically with $SPTs. It transforms real-world game outcomes into quantifiable, trustless, on-chain results. Every stat, goal, assist, or defensive action becomes a factor that defines token value and reward potential.

#### Core Principles

SVM’s scoring model is designed to be:

* **Transparent:** Every scoring metric is clearly defined and implemented on-chain.
* **Performance-Driven:** Rewards are based purely on real-world athletic performance.
* **Data-Verified:** All inputs are sourced via decentralized oracles from verified, reliable sports data providers.
* **Expandable:** The scoring framework is designed to accommodate new sports, leagues, and stat categories as the protocol grows.

#### Role of Scoring in the Ecosystem

Athlete performance scores determine:

* **Staking Rewards:** The better an athlete performs, the more rewards their stakers earn.
* **Airdrop Eligibility Multipliers:** Scoring influences multipliers used in Sporties and airdrop allocation.
* **Leaderboard Standings:** In the Free-to-Play experience, scoring affects how users rank and qualify for Sporties-based prizes.
* **Boosting Dynamics:** Scoring can trigger boosts that temporarily increase reward rates for high-performing tokens.

#### Score Calculation Methodology

Each athlete’s score is calculated on a match-by-match basis using:

* Raw stat inputs from trusted sports data APIs
* Predefined scoring rules tailored to each sport
* Weighted modifiers for certain positions or roles (e.g., defenders vs forwards)

Scores are calculated, verified, and published after each match. Once validated, these scores update staking rewards and trigger any relevant contract events (e.g., token boosts or Sporties generation).

#### Example Use Case

Let’s say a football player scores 1 goal and 1 assist in a match. Based on the Football Scoring Matrix (see subpage), this might give them a score of 15 points. If you’ve staked their $SPT tokens, you’ll receive Sporties proportionally to your stake and their score.

#### Governance and Scoring Adjustments

The scoring system is governed by the SVM DAO. This means:

* Scoring formulas can evolve over time based on feedback and sport-specific adjustments.
* The community can propose and vote on changes to metrics, weights, and thresholds.
* New sports can be onboarded with unique matrices after DAO review and testing.

#### What’s Next

Currently, football (European ,real football) is the first fully integrated sport in the SVM ecosystem. You can view the full breakdown of football-specific scoring on the dedicated **Football Scoring Matrix** page.

Additional sports such as basketball, tennis, and MMA are under consideration for future integration.
