# What is RChain?

::: tip Purpose
RChain is a general-purpose smart contracting platform and blockchain. Its aim is to provide a decentralized, economically sustainable public compute infrastructure of internet scale.
:::

In order to achieve this, a fundamentally different model of computation was needed. The technology that underlies RChain is the Rho-calculus, which enables concurrent computation on distributed systems. The RhoVM is at the very heart of the RChain network.

Contract logic on RChain is written in the Rholang language, which represents a bare-bones abstraction of the Rho-calculus. The platform is secured through a Proof of Stake consensus algorithm: Casper CBC.

### Technology

The most significant technological differentiator between RChain and other blockchain platforms is its computational model of the [Rho-calculus](platform/research.md#rho-calculus), which is _inherently concurrent_. Key properties that developers are excited about:

* **Concurrent** distributed systems programming
* **Capability Security** to support robust composition and cooperation without vulnerability
* **Namespaces** for sharding that scales like nature
* **Behavioral Types** that enable formal verification

### Governance

RChain aims to built its technology openly and together. The main steward of the RChain platform is the [**RChain Cooperative**](ecosystem/rchain-coop.html). The Coop is committed to radical transparency. The members of the Coop make governance decisions through voting, the election of board members, and other key players. As of October 2018, the Coop has over 1600 members from across the globe.


### Economics

The cryptocurrency associated with the RChain blockchain is called _REV_. Transaction costs are expressed in _Phlogiston_. These terms can be thought of as similar to "Ether" and "Gas" on the Ethereum platform, respectively.

Since consensus is achieved through PoS validators, there is no notion of 'mining' on RChain.
<!-- I think the "seniorage" stuff means this isn't true:
All tokens are minted in the genesis block.
-->
Total supply of REV is [1,000,000,000](https://etherscan.io/token/0x168296bb09e24a88805cb9c33356536b980d3fc5). A [distribution of RHOC](https://github.com/rchain/reference/blob/master/finance/rhoc.md) in and around the coop is updated from time to time.

[Becoming a validator](https://rchain-docs.netlify.com/ecosystem/token-economics.html)
is the way to earn transaction fees.
