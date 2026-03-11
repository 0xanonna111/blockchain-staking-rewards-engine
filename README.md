# Staking Rewards Engine

This repository provides a high-performance, secure staking mechanism for DeFi protocols. Users can stake a specific ERC-20 token and earn rewards in the same or a different token based on the duration of their stake.

## Features
- **Time-Based Rewards:** Accrues rewards per second for precision and fairness.
- **Pull-Based Distribution:** Users "pull" their rewards, making the contract highly gas-efficient.
- **Secure Withdrawals:** Implements emergency functions and re-entrancy protection.
- **Configurable APY:** Easily adjustable reward rates for protocol governance.

## Technical Overview
The contract calculates rewards using the formula:
$Reward = StakedAmount \times RewardRate \times TimeElapsed$

## Setup
1. Deploy the staking contract.
2. Transfer reward tokens to the contract address.
3. Users approve the contract and call `stake()`.

## License
MIT
