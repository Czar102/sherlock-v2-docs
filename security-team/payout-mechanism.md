# Payout Mechanism

The on-chain mechanism for the security team payout is not very complex. When Sherlock takes on a new protocol, the percent of fees allocated to the security team will be decided. This will likely be in the range of 10-20% of the total fees paid to Sherlock. That payment will accrue into a special pool which governance can transfer to a governance-controlled address at any time by calling a transfer function. The rest of the payout factors (tranched vesting schedule, implied hack values, etc.) will be calculated off-chain and payments will be made on a scheduled basis. Bringing this functionality entirely on-chain doesn't provide a ton of added value, which is why Sherlock will start out with a simplified (and partially off-chain) payout mechanism. However, this mechanism will be automated and decentralized over time.