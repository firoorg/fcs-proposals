---
layout: fr
title: Integrating XZC to BTCPayserver
author: The Arcadia Group
date: December 18, 2019
amount: 970
milestones:
  - name: Sprint 1 - Integrating Zcoin and Sigma Spend Reception & QA/Testing
    funds: 50% (484.5 XZC)
    done:
    status: unfinished
  - name: Sprint 2 - Finalizing and Testing BTCPayserver for Zcoin
    funds: 50% (485.5 XZC)
    done:
    status: unfinished
payouts:
  - date:
    amount:
  - date:
    amount:
---
#Proposal
Our plan for building a custom fork of the BTCPayserver software can be broken down into, discovery, analysis and development. We have worked previously with Zcoin's codebase with our work on [Reciever Address Privacy](https://github.com/zcoinofficial/zcoin/tree/feature/rap). While working on BTCPayserver will likely not require modification to the core codebase, unless zcoin is missing RPC Calls, which there may be as Zcoin doesn't  always have all of the more recent changes to RPC functionality from upstream Bitcoin and Dash. We at Arcadia are big on Zcoin, and would love to continue contributing to the community through our peripheral development, to assist in making Zcoin just a bit more accessible. 

<b> The cost of the following section has been modified thanks to new information </b>
We will review the current BTCPayServer codebase accounting for work that has been done to integrate and identify the key elements of the codebase that need to be modified to work with Zcoin as well as the potential modifications needed to work with and accept Sigma spends. The motivation of this discovery will be to explore both the web-based eCommerce capabilities for a shopping cart or a buy now button, and the physical-based point of sale system integration capabilities.

Once the discovery is done, we will assess the current roadmap of BTCpayServer as it pertains to Zcoin's existing RPC functionality, and audit the capabilities with regards to improvements that might need to be made. Only then will we be able to generate an accurate assessment of the order in which things need to be done and will get started on the actual integration process.

BTCPayserver has a great deal of functionality that is not easily supportable on Zcoin (fiat settlement via Bitpay being one example), so we are limiting our scope on heavily tested functionality. The core functionality that would be focused upon during development would include, 
* The ability to accept standard Zcoin Transactions 
* The ability to accept Sigma Spends as a payment
* Generic BTCPayServer Functionality for accepting XZC payments via:
* E-Commerce
* Point of Sale
* Payment Buttons

The estimated timeframe on this project would be approximately two calendar weeks,
The team breakdown for this engagement would be:

* 1 Full Time Developer 
* 1 UI/UX
* 1 Project Manager
