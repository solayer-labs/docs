# Introduction

There exists a design space of distributed applications that require active validation of their rules in ways that cannot be sufficiently implemented using smart contracts on programmable blockchains. These are services like data availability systems, oracle networks, cross-chain bridges, and more. This kind of distributed application is commonly referred to as an _actively validated service_, or AVS, a term coined by the EigenLayer team.

AVSs face several major challenges to the security of their protocols. For instance, each must bootstrap an independent network of protocol participants and incentivize honest behavior. Often this involves the creation of a digital asset native to the AVS network or heavy permissioning, both approaches having a myriad of challenges on their own. In cases where several AVSs are secured by their own native assets, they do not share their security. This means that this approach to distributed applications results in weaker, more fragmented economic security than the traditional approach of smart contracts running on one blockchain network.

Restaking is a mechanism which offers solutions to these problems, enabling AVSs to share economic security and collectively leverage the security of established proof-of-stake networks.
