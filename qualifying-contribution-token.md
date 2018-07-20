Qualifying Contribution Token
=============================

Introduction
-------------

This document outlines the concept for a token, which is given to contributors of coindashboards.com for their dedication, time spent, skill and knowledge provided to the organization. A contributor for that matter is everyone, who adds some form of _value of notable substance_ to the website, the analytics and the organization itself, called a Qualifying Contribution.

The concept of Qualifying Contributions stems from the work of [FairShares](http://www.fairshares.coop), which is a development model for self-governing enterprises with a unique multi-stakeholder approach to increasing value within and around an organization. What coindashboards.com defines as Qualifying Contributions will be developed and updated continuously and made available on GitHub in [qualifying-contribution-list.md](qualifying-contribution-list.md).

Technology
----------

The token will be issued via an Ethereum Smart Contract.

Concept
---------

__Token Dynamics__

The coindashboards.com organization will initially create 200,000 tokens named __CDB-One__, which are spendable until Ethereum  block 8.000.000 has been reached. The remaining tokens are burned thereafter. __CDB-One__ is given to contributors as per the list of definitions of Qualifying Contributions and remain valid indefinitely.

Following Ethereum block 8,000,001, coindashboards.com organization will create 200,000 new tokens named __CDB-Two__, which are spendable until Ethereum block 10,000,000 has been reached. The remaining tokens are burned thereafter. __CDB-Two__ is given to contributors as per the list of definitions of Qualifying Contributions and remain valid indefinitely.

Following Ethereum block 10,000,001 this token-issuing-dynamic continues with __CDB-Three__ and eventually beyond in a similar way.


__Token value__

Owners can at any time trade their tokens on an exchange. However, with block 8,000,000 reached, owners of __CDB-One__ have additional choices of how to use these tokens:

* Swap their CDB-One tokens with CDB-Two tokens at a discounted rate, upon which those CDB-One tokens are burned. The _discount rate_ is 25%.

* Sell their CDB-One tokens back to the coindashboards.com organization in return for Ether (ETH), upon which those CDB-One tokens are burned. The exchange rate is determined as described below.

With block 10,000,000 reached and CDB-Three issued, now owners of CDB-Two have the choices outlined above. This eventually continues with block 12,000,000 reached, CDB-Four issued and CDB-Three sold or exchanged.

The advantage of splitting the token into time intervals is that it allows for more flexibility in governance, design and valuation given the status of the organization and its projects.


__Exchange Rate on Buy Back__

The _exchange rate_ for the buy-back is determined by 

* Timestamp: 23:59 h of the last day of the month in which block 8m has been reached (block 10m , 12m respectively)
* Net profit after tax gained by the organization up until timestamp (A)
* Total amount of tokens issued to contributors before block has been reached (B)
* ETH/EUR or ETH/USD price at bitfinex.com at timestamp (C)

The formula is as follows: ((A * 0.5) / B) * C

The organisation will release an _estimate_ on this exchange rate by week 9 the latest following the timestamp. The purchase of tokens by the organization at the _definite_ exchange rate can only be pursued when the accounting has been fully prepared and cleared.



