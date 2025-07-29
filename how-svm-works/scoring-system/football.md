# ⚽ Football

This matrix defines how football player performance is converted into on-chain scores in the SVM ecosystem. These scores power staking rewards, token utility, and leaderboard rankings in both crypto and free-to-play modes.

Stats are sourced from trusted providers via decentralized oracles and verified on-chain.

#### 🟩 Positive Actions

| Stat/Event         | Description                                                  | Points |
| ------------------ | ------------------------------------------------------------ | ------ |
| Shot               | Attempted shot that is off target, hits post/bar, or blocked | +1     |
| Shot on Target     | Shot that would score if not saved or blocked off the line   | +4     |
| Goal               | Goal scored                                                  | +20    |
| Assist             | Pass leading directly to a goal                              | +12    |
| Key Pass           | Pass leading to a shot on/off target (includes goals)        | +5     |
| Interception       | Breaking up an opposition pass                               | +2     |
| Penalty Won        | Player is fouled inside the penalty area                     | +10    |
| Tackle             | Winning possession or forcing the ball out of play           | +3     |
| Block              | Blocking an opponent’s shot                                  | +2     |
| Successful Dribble | Beating an opponent with control                             | +3     |
| Save               | Goalkeeper saves a shot                                      | +7     |
| Penalty Save       | Goalkeeper saves a penalty                                   | +20    |
| Winning Team       | Player is on the winning team                                | +20    |
| Clean Sheet        | Team concedes zero goals (Defenders & Goalkeepers only)      | +20    |

***

#### 🟥 Negative Actions

| Stat/Event       | Description                                         | Points |
| ---------------- | --------------------------------------------------- | ------ |
| Goal Conceded    | Goal allowed (applies to Goalkeepers and Defenders) | -4     |
| Own Goal         | Scoring against own team                            | -20    |
| Yellow Card      | Receiving a yellow card                             | -4     |
| Red Card         | Receiving a red card                                | -20    |
| Penalty Missed   | Missed penalty (wide, post, or saved)               | -7     |
| Penalty Conceded | Conceding a penalty (includes handball)             | -10    |
| Dispossessed     | Losing the ball to an opponent (tackled)            | -1     |

***

#### ⚙️ Notes & Application

* Stats apply per player, per match.
* Verified through oracles after official match data finalizes.
* Some stats (like Clean Sheet or Goal Conceded) apply only to specific positions.
* Used in both crypto and free-to-play dApps to calculate staking and leaderboard rewards.
