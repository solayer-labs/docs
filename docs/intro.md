---
slug: /
sidebar_position: 1
title: Welcome 🖐️
---

Solayer is Solana's own restaking protocol

---

TODO move below into separate page

### What is an AVS?

There exists a design space of distributed applications that require active validation of their rules in ways that aren't feasible for implementation as smart contracts on programmable blockchains. These are services like data availability systems, oracle networks, cross-chain bridges, and more. This kind of distributed application is commonly referred to as an *actively validated service*, or AVS, a term coined by the EigenLayer team.

AVSs face several major challenges to the security of their protocols. For instance, each must bootstrap an independent network of protocol participants and incentivize honest behavior. Often this involves the creation of a digital asset native to the AVS network or heavy permissioning, both approaches having a myriad of challenges on their own. In cases where several AVSs are secured by their own native assets, they do not share their security. This means that this approach to distributed applications results in weaker, more fragmented economic security than the traditional approach of smart contracts running on one blockchain network.

Restaking is a mechanism which offers solutions to these problems, enabling AVSs to share economic security and collectively leverage the security of established proof-of-stake networks.

### What is restaking?

On decentralized blockchain networks secured by proof-of-stake, such as Ethereum and Solana, participants have the ability to *stake* some of their assets into the network. In exchange, they receive the opportunity to validate that the activity on the network behaves according to some set of rules that comprise the network's protocol. If one of these validators attempts to declare spurious activity as genuine, other validators can destroy the dishonest validator's staked assets. Validators are rewarded with more digital assets by the protocol for their contribution to the security of the network.

On some of these proof-of-stake networks, validators can use an application-layer *restaking* system to opt-in to validate activity against additional sets of rules that define additional protocols. These protocols can provide validators with more rewards than they would otherwise earn by solely validating for the network's base protocol. If validators break the additional rules they agreed to, other participants in the restaking system can destroy their restaked assets.

Constructing an AVS as a protocol secured by a restaking system sidesteps many of the hurdles it might face, as outlined in the previous section. This reduces the barriers to entry for new AVSs, creating the conditions for exiciting innovation to happen.

### Why restake on Solana?

---

TODO this on next page, basically details about previous concepts

TODO make a better structure than what is below

### Delegation / Operators

### Liquid / Native Staking

### Liquid / Native Restaking

---

TODO another page explaining the current state of the project and the intended path forward

TODO security section
