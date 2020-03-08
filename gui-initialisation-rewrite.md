---
layout: fr
title: Proposal to Rewrite Initialisation Logic in the Zcoin GUI Client
author: sproxet
date: March 7, 2020
amount: 890
milestones:
  - name: Begin Work
    funds: 45.5% (405 XZC)
    done:
    status: unfinished
  - name: Finish Work
    funds: 54.5% (485 XZC)
    done:
    status: unfinished
payouts:
  - date:
    amount:
  - date:
    amount:
---

# Proposal to Rewrite Initialisation Logic in the Zcoin GUI Client


Over a period of several months in 2019, I ([sproxet](https://github.com/zcoinofficial/zcoin-client/commits?author=sproxet)) rewrote the vast majority of the [Zcoin GUI Client](https://github.com/zcoinofficial/zcoin-client), to bring cleaner code, major performance improvements, and a myriad of bug fixes, but sadly was not able to complete the project due to budgeting difficulties. The last bit of logic in the client that was not refactored, related to initialisation, unfortunately still possesses a convoluted design which has resulted in poor performance and numerous bugs, which in turn have caused significant difficulties in testing and still prevent a stable release of the client.

Should this proposal be funded, it will enable the initialisation code to be for the most part rewritten, which will fix several troublesome bugs, provide a good basis for a stable release, and lessen the technical burden of any future improvements to the client that might be required.

The funding requested for this project is an initial instalment of XZC 405 (approximately USD 2250 at the time of this writing), followed by XZC 485 (USD 2250 plus an additional 20% due to uncertainties associated with asset volatility) at project completion. The expected timeline for the project is two to three weeks, however development time is notoriously difficult to estimate and therefore cannot be guaranteed.