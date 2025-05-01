# Reputation System (RepScore)

## How RepScore is Calculated

RepScore measures a user’s reliability and contribution to the Solvex ecosystem:

- **Initial Score:** All users start with a baseline RepScore (e.g., 100).
- **Earning Points:**
  - +10 for each correct validation (aligned with majority).
  - +50 for submitting a high-quality proposal (validated by community).
  - +20 for consistent participation (e.g., validating 10 proposals in a month).
- **Losing Points:**
  - -20 for incorrect validation (against majority).
  - -100 for malicious behavior (e.g., spam proposals, detected by AI).

## Impact of RepScore

- **Voting Weight:** Higher RepScore increases a user’s influence in validations.
- **Rewards:** Users with higher RepScore earn larger $SOLVEX rewards.
- **Access:** Certain high-stakes proposals require a minimum RepScore to participate.

## Penalties for Abuse

- **Temporary Bans:** Users with critically low RepScore (e.g., <50) may be temporarily excluded from validations.
- **Token Slashing:** Malicious actors risk losing staked $SOLVEX.
- **AI Monitoring:** The AI layer flags suspicious behavior, ensuring fairness.
