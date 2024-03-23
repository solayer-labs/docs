# Page

#### What is an AVS?[​](https://docs.solayer.org/overview/basics#what-is-an-avs) <a href="#what-is-an-avs" id="what-is-an-avs"></a>

There exists a design space of distributed applications that require active validation of their rules in ways that cannot be sufficiently implemented using smart contracts on programmable blockchains. These are services like data availability systems, oracle networks, cross-chain bridges, and more. This kind of distributed application is commonly referred to as an _actively validated service_, or AVS, a term coined by the EigenLayer team.

AVSs face several major challenges to the security of their protocols. For instance, each must bootstrap an independent network of protocol participants and incentivize honest behavior. Often this involves the creation of a digital asset native to the AVS network or heavy permissioning, both approaches having a myriad of challenges on their own. In cases where several AVSs are secured by their own native assets, they do not share their security. This means that this approach to distributed applications results in weaker, more fragmented economic security than the traditional approach of smart contracts running on one blockchain network.

Restaking is a mechanism which offers solutions to these problems, enabling AVSs to share economic security and collectively leverage the security of established proof-of-stake networks.

#### What is restaking?[​](https://docs.solayer.org/overview/basics#what-is-restaking) <a href="#what-is-restaking" id="what-is-restaking"></a>

On decentralized blockchain networks secured by proof-of-stake, such as Ethereum and Solana, participants have the ability to _stake_ some of their assets into the network. In exchange, they receive the opportunity to validate that the activity on the network behaves according to some set of rules that comprise the network's protocol. If one of these validators attempts to declare spurious activity as genuine, other validators can destroy the dishonest validator's staked assets. Validators are rewarded with more digital assets by the protocol for their contribution to the security of the network.

On some of these proof-of-stake networks, validators can use an application-layer _restaking_ system to opt-in to validate activity against additional sets of rules that define additional protocols. These protocols can provide validators with more rewards than they would otherwise earn by solely validating for the network's base protocol. If validators break the additional rules they agreed to, other participants in the restaking system can destroy their restaked assets.

Constructing an AVS as a protocol secured by a restaking system sidesteps many of the hurdles it might face, as outlined in the previous section. This reduces the barriers to entry for new AVSs, creating the conditions for exiciting innovation to happen.

#### Why restake on Solana?[​](https://docs.solayer.org/overview/basics#why-restake-on-solana) <a href="#why-restake-on-solana" id="why-restake-on-solana"></a>

AVSs built on top of the security of restaked Solana receive a great deal of indirect benefit from Solana's high throughput and cheap blockspace. When these services need to signal or settle anything on-chain, they can do so quickly and cheaply. This opens up greater possibilities for the kinds of services that can be built when compared against similar restaking solutions built on less performant networks like Ethereum.

[\
](https://docs.solayer.org/category/overview)Liquid staking tokens[​](https://docs.solayer.org/overview/additional-features#liquid-staking-tokens)

Liquid staking services are a wildly popular way for users who would like to stake their assets to receive a liquid token in exchange while their assets remain locked. These applications often serve an additional purpose as a way for users who don't have the minimum capital required to stake and become a validator to instead pool their capital with others to reach the minimum stake, and often also delegate operation of the validator software to a third party. Solayer, in addition to supporting users who provide native SOL for staking and restaking, supports the restaking of several liquid staking tokens linked to already-staked SOL. As of now, the supported liquid staking tokens are JitoSOL, mSOL, and bSOL.

#### Delegated AVS operation[​](https://docs.solayer.org/overview/additional-features#delegated-avs-operation) <a href="#delegated-avs-operation" id="delegated-avs-operation"></a>

Running software to validate a variety of AVS protocols is a task that is best left for sophisticated users who are capable of running the software efficiently and reducing the risk of service distruption. Users simply looking to receive rewards for committing their assets to be restaked may not be sufficiently sophisticated operators of AVS software to operate it safely. Or, users might simply prefer to avoid the inconvenience of running AVS software themselves.

In any case, it is possible for users restaking their assets to delegate the operation of AVS software to a sophisticated entity willing to operate the AVS software on their behalf.

\
