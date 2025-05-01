# Technical Architecture

## Integration with Solana

Solvex is built as a layer-2 protocol on Solana, leveraging its high-performance blockchain:

- **Transaction Processing:** All submissions, validations, and rewards are recorded as Solana transactions.
- **Speed and Cost:** Solana’s 400ms block time and low fees ensure efficient operations.
- **Sealevel Runtime:** Solvex smart contracts run in parallel, supporting simultaneous validations.

## Role of Smart Contracts

- **Proposal Management:** Stores proposal metadata and validation status.
- **Reputation Tracking:** Updates RepScore based on user activity.
- **Reward Distribution:** Automatically allocates $SOLVEX to validators.
- **Governance:** Enables $SOLVEX holders to propose protocol changes.

## Security and Decentralization

- **Immutable Records:** All actions are stored on Solana’s blockchain, ensuring transparency.
- **AI Safeguards:** The AI layer prevents spam and malicious proposals.
- **Decentralized Validation:** No single entity controls outcomes, as consensus relies on community votes.
