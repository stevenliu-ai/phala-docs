---
description: Cross-chain bridge for transferring assets between Phala and other blockchains.
title: Overview
---

Phala has upgraded to use Superbridge as the cross-chain tool for Ethereum Layer 1 (L1) and Layer 2 (L2). Superbridge is a cross-chain bridge solution optimized for bridging assets between Ethereum L1, L2 rollups (such as Arbitrum and Optimism), and other chains, supporting seamless and secure token transfers.



## What is Superbridge? <a href="#what-is-superbridge" id="what-is-superbridge"></a>

Superbridge is an advanced cross-chain bridge solution enabling secure and efficient asset transfers between Ethereum Layer 1 (L1) and Layer 2 (L2) networks. It supports ETH and ERC-20 tokens and incorporates a mandatory challenge period of about 7 days for withdrawals from L2s to L1 to ensure transaction finality and security in the optimistic rollup model. Deposits are fast, but withdrawals follow this waiting period as a security measure. Superbridge is an integral part of Phala’s upgraded cross-chain tools, ensuring a seamless user experience and robust asset safety.

For more information, see the [Superbridge documentation](https://help.superbridge.app/en/).



## Superbridge Cross-Chain Waiting Time

The typical waiting time for withdrawals using Superbridge on L2 rollups involves a mandatory challenge period for security reasons. This waiting period is generally about **7 days**. This is due to the optimistic rollup security model, where a delay is required to allow for fraud proofs and ensure the safety of funds before finalizing the withdrawal back to Ethereum L1 or settlement chains. Deposits to L2 chains are usually faster, often completed within minutes, but withdrawals take longer due to this challenge period.
