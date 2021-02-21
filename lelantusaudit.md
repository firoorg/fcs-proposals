---
layout: cp
title: Lelantus Code Audit
author: Zcoin Core Team
date: May 18, 2020
amount: 14800
milestones:
  - name: Commencement
    funds: 7400
    done:
    status: unfinished
  - name: Completion
    funds: 7400
    done:
    status: unfinished
payouts:
  - date:
    amount:
  - date:
    amount:
---
A well audited and solid Lelantus implementation is critical for Zcoin. A vulnerability in Lelantus may result in a break of anonymity or hidden inflation of supply. We are seeking funds for a third party code audit of Lelantus cryptography and implementation.

While the core team has renewed development funding post halving, this comes into effect only in September and even then assuming similar market conditions, would have a significant impact on the Core Team's reserve funds that are used to tide over challenging market conditions.

From our discussions with various code audit companies (for e.g. [Trail of Bits](https://www.trailofbits.com/), [SmartDEC](https://smartdec.com/)), a reasonably comprehensive review of the Lelantus cryptographic library and the wallet implementation code will cost around USD64,000. We will update this proposal from time to time to reflect the actual cost.

## Scope of Audit

A smaller scope that just covers the implementation without going into the cryptography would be quite a bit cheaper but if the budget permits, it makes more sense to have a reasonable coverage of both.

We intend to cover the following in the audit but will subject to change depending on amount raised and finalized quotes.

1. Lelantus cryptographic library
2. Lelantus RPC functions
3. Wallet functionality in relation to Lelantus
4. Wallet database in relation to Lelantus
5. Lelantus state
6. Accepting Lelantus transactions into mempool, block connection and disconnection, etc
7. Miner related changes
8. Transaction and auxiliary structures
9. HD Lelantus mints.
10. Evaluation of Lelantus cryptography as described in paper 

## Timeframe

We hope to begin audit in July and the code review is espected to take about 2-4 weeks after which we will take another few weeks to incorporate the fixes as recommended by the audit. The results of the audit will be made public.

## Excess Funds

Should the code audit be cheaper than anticipated, the balance will be kept for future code audits which may be required as we will be implementing Lelantus Direct Anonymous Payments after the initial deployment of Lelantus and/or our [code bounty program](https://zcoin.io/zcoin-vulnerability-bounty-program/).

Should the core team have excess funds we will also contribute towards this proposal and disclose these amounts.

## Acknowledgement of Donation

Should you wish to be named as a donator in the audit, you can optionally let us know and we will include your name/organization name in any announcement relating to the Lelantus code audit.
