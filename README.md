# satoshichain
Smart Contract Platform for Bitcoin

**Motivation**

Bitcoin is a digital currency created in January 2009 by Satoshi Nakamoto. The ideas outlined in the original whitepaper envisioned Bitcoin to become peer-to-peer electronic cash for payments. However, the Bitcoin we have today is acknowledged as a store-of-value rather than a payment medium. It is time to create more functionalities for Bitcoin by creating an Ethereum-based sidechain using Bitcoin as its native cryptocurrency and Nakamoto (NKMT) for governance and consensus participation.

**Bitcoin as a payment medium is history**

Some have with Bitcoin as a medium of payment is the relatively slow transaction speed or TPS. A new block in the Bitcoin network is created every 10 minutes. This equates to a theoretical ceiling of around 7 TPS. As a store-of-value, the low transaction throughput is manageable, but transaction speed is critical for everyday use. The SegWit upgrade and Lighting Network implementations have improved the overall transaction throughput speed of Bitcoin, but in 2021 it has become evident that Bitcoin is more compared to gold and an alternative type of investment and not a payment medium. Other Bitcoin-based cryptocurrency models somewhat evidence this. 

Litecoin and Decred improved upon the original Bitcoin codebase to improve scalability but have yet to see widespread commercial adoption as a payment medium. The existing crypto-payment solutions go through existing payment service providers, and most enterprises do not directly accept cryptocurrency over the network as payment. The diehard supporters of Bitcoin as a payment medium splintered into Bitcoin Cash in August 2017. The implementation of SegWit created a divide within the Bitcoin community. Many dissenters preferred to increase the block size to 8MB, as they believed it offered a superior scaling solution. Bitcoin Cash eventually split into Bitcoin Cash and Bitcoin Satoshi Vision due to internal community dissents about Canonical Transaction Ordering Route. Bitcoin Cash experienced another hard fork in November 2020 by Bitcoin ABC, rebranding to eCash and transitioning into PoS consensus. 

None of the Bitcoin variants surpasses Bitcoin in terms of transaction value over each native network. This signifies none has yet to overtake Bitcoin, despite the enhancement in scalability. The version of Bitcoin today, where CDBCs are sprouting left and right, is not to become a global digital currency. It is now a store of value and the centerpiece for all things digital. 

**Bitcoin was criticized to create no value**

Warren Buffet famously stated on CNBC in February 2019. "Bitcoin has no unique value at all, and it doesn't produce anything. You can stare at it all day, and no little Bitcoins come out or anything like that. It's a delusion, basically." The truth is Ethereum has paved the roadmap for cryptocurrencies that have the potential to create real value. This can be exemplified in the many dApp ecosystems, including DeFi and NFTs that we see today. Empowering Bitcoin with smart contract functionalities may become a way Bitcoin can create value perceived by institutions.

**Solution**

Create an EVM-compatible network using Bitcoin as the native cryptocurrency. 

Why is this not crazy? 

Well, we already witnessed the success of the Binance Smart Chain and the plethora of exchange based networks created in 2021. This includes Cronos from Crypto.org, KuCoin Community Chain from KuCoin, Huobi ECO Chain from Huobi, OKEx Chain from OKEx, etc. Initially, most of the exchanges created a Tendermint based BFT, like Binance Chain, mainnets and realized nobody cares to use decentralized networks without smart contract functionalities. Most exchange-based smart chain networks use PoA or PoSA for consensus. The launch of BSC, based on PoA and DPoS, and its success shows that people only care about a few things. Can users use the network or develop on it like Ethereum, and people care less about decentralization.

The fact that most of these chains use PoA, proof-of-authority, where decentralization is not the primary concern but has garnered massive support due to convenience speaks one thing. Like everything capitalism, money speaks louder than words. Decentralization can be obtained after commercial success is the main message accepted in the industry based on commercial adoption. 

The proposal for Satoshi Chain is to create a PoA consensus-based network that is EVM compatible. Like Binance Smart Chain, the native cryptocurrency for the network will not be new. Bitcoin, or Satoshi Chain Bitcoin (SCBTC), will become the native cryptocurrency for the Satoshi Chain network. 

**What?! How do you even do that?**

Create a new network like BSC, but call it the Satoshi Chain. And instead of BNB we use Bitcoin. Create a bridge to enable BTC exchange for Satoshi Chain BTC (SCBTC). Provide BTC bridge supporters with Nakamoto (NKMT) based on time value weight. Nakamoto emission duration will last until Bitcoin Halving 5, when block rewards are dropped to 1.5625 expected in 2028. NKMT is needed to participate in Satoshi Chain consensus, PoA, and earn fees from the network. People can use Bitcoin like Ethereum using SCBTC on the Satoshi Chain. SCBTC is the native token on Satoshi Chain and is used to pay transaction fees and interact with smart contracts. BTSC is a 1:1 peg to BTC and can be obtained by the BTC-SCBTC bridge. The network will not have natural emission for SCBTC as it is Bitcoin represented on an Ethereum-based sidechain. 

**Steps to create Satoshi Chain**

1. Like BSC, create a new token to replace ETH, in this case, Satoshi Chain Bitcoin (SCBTC)
2. Create a bridge using either RenVM like tech or custody-based like WBTC: This is dependent on what kind of initial Bitcoin stakers we can get.
3. Any Bitcoin created into Satoshi Chain will have a decimal of 18; this is for Ethereum network compatibility. Just need to make sure that any transactions related to the creation and burning of SCBTC and BTC  requests must stop at eight decimal points like Bitcoin on the bridge. This is more related to burn and claiming SCBTC for transfer back to the BTC network.
4. Native network will initially be PoA, aka we get to choose who does consensus
5. Network will not have inflation, as the native token is based on BTC. That means consensus participants will earn only through tx fees since the network has no natural inflation, like all those smart contract supported networks made by all the exchange coins. But, all fees are based on SCBTC, an equivalent to BTC. Also, Bridge participants can get to participate in consensus by receiving NKMT.
6. PoA participation is dictated by a secondary token called Nakamoto (NKMT). Participants who own Nakamoto and provide Bitcoin to the BTC-SCBTC bridge can become validators to earn network transaction fees from the Satoshi Chain.
7. Jumpstart Satoshi Chain with three DAO initiatives. Development of Satoshi Chain block explorer, Satoshi Chain DEX(Uniswap V2-like), and Satoshi Chain Launchpad. Satoshi Chain DEX and Satoshi Chain Launchpad will have their native token and be developed by the community. To bootstrap, the successful launch of the network, a certain percentage of tokens for the Satoshi Chain DEX and Satoshi Chain Launchpad will be airdropped NKMT holders. NKMT can only be obtained by providing Bitcoin to the BTC-SCBTC bridge. The first three initiatives will be funded with funds from the DAO from the newly created NKMT.

**Design Principles**

1. Standalone Blockchain: technically, Satoshi Chain is a standalone blockchain instead of a layer-2 solution for Bitcoin. Most Satoshi Chain fundamental technical and business functions should be self-contained to run well even if the Bitcoin network stopped. The Bitcoin-Satoshi Chain Bitcoin bridge is used to lock Bitcoin to the network, so consensus participants will have a stake in the Satoshi Chain. However, Bitcoin will be required to participate in the future PoSA(Proof-of-staked-Authority) consensus where NKMT and BTC staking are needed to validate transactions.
2. Ethereum Compatibility: The first practical and widely-used Smart Contract platform is Ethereum. To take advantage of the relatively mature applications and community, Satoshi Chain chooses to be compatible with the existing Ethereum mainnet. This means most of the dApps, ecosystem components, and toolings will work with Satoshi Chain and require zero or minimum changes; Satoshi Chain nodes will require similar (or a bit higher) hardware specifications and skills to run and operate. The implementation should leave room for Satoshi Chain to catch up with further Ethereum upgrades. The network will support ERC-20 tokens and other token standards with the changed name SRC-#. SRC stands for "Satoshi Chain Request for Comment."
3. Staking Involved Consensus and Governance: Staking-based consensus is more environmentally friendly and leaves more flexible options to community governance. Consensus will have three stages for the Satoshi Chain network. The initial network testnet will operate on full PoA where all validators are chosen by the DAO. The second stage will transition into the PoSA model where validators are required to have both Bitcoin, in the BTC-SCBTC, bridge, and NKMT staked to participate in governance and consensus. The final step would be full PoS based on the staked amount of dual NKMT and Bitcoin.
4. Native Cross-Chain Bridge: Satoshi Chain will be implemented with native support for a cross-chain bridge between Bitcoin and Satoshi Chain Bitcoin. The communication protocol should be bi-directional, decentralized, and trustless, obtained with RenVM technology. However, this topic needs further investigation as the off-chain custody model may require institutional investors to partake in consensus.

**Consensus**

Block production time should target below 5 seconds
The finality of transaction should be less than 1 minute
There is no inflation of native token: SCBTC, the block reward is collected from transaction fees, and it will be paid in SCBTC
It is compatible with the Ethereum
It allows modern proof-of-stake blockchain network governance, using NKMT and BTC

**1st Stage PoA**

Conditions for PoA: 
Valid and trustworthy identities: validators need to confirm their real identities.
Difficulty to become a validator: a candidate must be willing to invest money and put his reputation at stake. Something at stake will reduce the risks of selecting questionable validators and incentivizes a long-term commitment.
A standard for validator approval: the method for selecting validators must be equal to all candidates. 
The perception of the PoA mechanism is that it foregoes decentralization. So one could say that this consensus algorithm model is just an effort to make centralized systems more efficient. The network will operate as PoA until consensus participants for future PoSA are decided through BTC-SCBTC bridge participation.

**2nd Stage PoSA**

The Proof-of-Staked-Authority (PoSA) consensus algorithm is a hybrid between the Proof-of-Staking and Proof-of-Authority consensus mechanism. Satoshi Chain is a blockchain that will implement a Proof-of-Staked-Authority consensus algorithm in the 2nd stage. The PoSA consensus model supports a shorter block time and lowers costs than PoW.

Satoshi Chain validators are participants who "stake" a certain number of NKMT, a governance token based on the SRC-20 standard. When they propose a valid block, they receive transaction fees as a reward for the transactions contained in that block. This means that no new SCBTC is minted to reward validators, but the reward comes from existing SCBTC tokens.

The number of active validators is limited to 21, and only active validators are eligible to validate transactions. Active validators are determined by ranking all validators according to the number of NKMT tokens they have. The top 21 validators with the highest number of NKMT become involved and take turns validating blocks.

While the PoSA consensus model allows for short block times and lower costs, it comes at the expense of network decentralization and security. Due to this PoSA consensus model, a user cannot simply start validating transactions of the Satoshi Chain themselves in the same way that they can with Bitcoin or Ethereum. PoSA is a permissioned network where consensus participation is limited to those with a stake in the network via BTC bridge support and NKMT staking.

**3rd Stage PoS**

Once the emission for NKMT is complete, the network can transition into a PoS consensus model to support complete decentralization. The core concept of needing to stake both Bitcoin on the BTC-SCBTC bridge and NKMT stays valid. The DAO, NKMT holders govern the ratio of NKMT required for Bitcoin stake.

**What is SCBTC?**

Satoshi Chain Bitcoin (SCBTC) is the native token on the Satoshi Chain network. Using the BTC-SCBTC bridge, the network supports BTC to migrate into the Satoshi Chain network. All transaction fees and smart contract interactions are paid with SCBTC and rewarded to validators. SCBTC is denominated by 18 decimals, unlike Bitcoin, which has 8 decimals. This is due to creating an Ethereum compatible native token. The difference in decimals is forced to be reconciled when users use the BTC-SCBTC bridge to burn SCBTC for BTC transfers into the Bitcoin network. SCBTC will follow denomination names according to Ethereum to increase Ethereum compatibility, which means the base unit for SCBTC is not Satoshi, but Wei.  

1000000000000000000	Wei (10^-18)
1000000000000000	KWei
1000000000000	MWei
1000000000	GWei (10^-9)
1000000	Szabo
1000	Finney
1	SCBTC (1)
0.001	KSCBTC
0.000001	MSCBTC
0.000000001	GSCBTC
0.000000000001	TSCBTC

**What is NKMT?**

Nakmaoto (NKMT) is the native governance token on the Satoshi Chain network. It is an SRC-20 token standard, like the ERC-20 token, used to participate in PoSA consensus. A separate governance platform for staking and consensus participation will be developed using NKMT. Based on the stage of the consensus method implemented, NKMT is used for staking to participate in block production and rewarded with SCBTC. Later on, the ratio of NKMT to Bitcoin to participate in consensus will be voted through governance. Early NKMT holders will benefit from being airdropped tokens for two main DAO initiatives: the Satoshi Chain DEX and Satoshi Chain Launchpad. 

NKMT can only be earned by providing Bitcoin to the BTC-SCBTC bridge. NKMT will only be available for earning until the 5th halving date of Bitcoin, expected in 2028. The initial emission for NKMT will be based on time-value weighted to equal the amount of Bitcoin required to stake when PoSA goes live. This means 1 Bitcoin staked to the BTC-SCBTC bridge for the entire duration will receive enough NKMT to stake 1 Bitcoin. If Bitcoin is only staked for half the time, the amount of NKMT rewards will only be worth 0.5 Bitcoin staking. 

**Emission Schedule**

**1st Stage PoA**

The total supply of NKMT is dependent on how much Bitcoin is put in the BTC-SCBTC bridge and the duration of the stake. 25% of all newly created NKMTs are sent to the DAO treasury, and another 25% is sent to the team wallet. 50% is awarded to BTC-SCBTC bridge supporters. Aside from the DAO treasury, all NKMT tokens are locked and non-tradeable. Because the DAO treasury is the only active holder of NKMT, and governed by NKMT holders, it is essentially centralized during the PoA stage. NKMT will be used for PoA consensus by initial network DAO members and to bootstrap projects via DAO initiatives.

**2nd Stage PoSA**

NKMT will continue to be rewarded to all BTC-SCBTC bridge providers, but the emission ratio will change in favor of bridge supporters. 15% NKMTs, and 5% to team wallets. 80% is provided to BTC-SCBTC bridge participants. The emission will end at the 5th Halving date of Bitcoin, expected in 2028. NKMT will be unlocked by the time PoSA is implemented. And governance participation is available by all NKMT holders.

**3rd Stage PoS**

By the time PoS is implemented, NKMT emission will halt. It is expected that transaction fees from the network will be enough to support the ecosystem. Despite how the system is based on PoS, the network will not be entirely based on NKMT. All governance participation still requires stakers to participate in the BTC-SCBTC bridge and stake NKMT to participate in PoS. The NKMT holders govern the ratio of BTC required per NKMT to participate in consensus.
