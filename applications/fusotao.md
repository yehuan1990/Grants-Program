
# W3F Grant Proposal

- Project Name: Fusotao Protocol
- Team Name: Fusotao Group
- Payment Address: 0xEae9B18766bBff360eC05fB6341CAD58ab4f1b01

## Project Overview :page_facing_up:

If this application is in response to an RFP, please indicate this on the first line of this section.

If this is an application for a follow-up grant (the continuation of an earlier, successful W3F grant), please provide name and/or pull request of said grant on the first line of this section.

### Overview
- A brief description of your project.
As an innovative paradigm of defi, Fusotao is a verification protocol for orderbook-based matching system using the paradigm of "execute off-chain, verify on-chain". 

- An indication of how your project relates to / integrates into Substrate / Polkadot / Kusama.
As an abstract protocol, PoM can either be built on existing blockchains as a series of contracts or run as an independent network. Considering the gas fee and latency, we have implemented Fusotao protocol over Substrate as a permissionless network which permits submitting proofs with zero-cost and low-latency.

- An indication of why your team is interested in creating this project.
As we all know, there are two ways to trade cryptocurrencies: by using orderbook-based matching systems (a.k.a CEX) or SWAPs (a.k.a DEX). The CEX is fast, low-cost but unsafe since deposition is necessary while the DEX stands opposite.
We are building a web3 infrastructure to help users can trade neither relying on human trust nor bearing the high latency and cost.


### Project Details
- Components & Technical specs
Fusotao Protocol is an abstract protocol composed of two core components: 
- verifier: a blockchain
- prover: an off-chain matching system
Currently, we have built the blockchain by the substrate as a standalone blockchain, and we also have a planB that deploy the protocol to other blockchains.
By trading on a fusotao integrated trading platform, users shouldn't transfer tokens to the platform, instead, they just need to authorize tokens. After authorization is accepted, the tokens are not going anywhere but move from "free" to "reserved" state in the same account. The only way to modify the reserved tokens is proving it, that's what the off-chain prover doing. The off-chain prover is a standard matching engine just like other orderbook-based matching systems, but plus an additional Proof of Matching procedure. The matcher will update the states within it immediately but the assets won't be affected until the proofs are submitted.
To have a better understanding, please review our demo video: https://youtu.be/NjwhsonPdHM

- Completely open source
All of our components are fully open-source. The matching system is offered to founders who would like to build a reliable DEX just like provers of Filecoin do.
To have a better understanding, please review our Technical Greenbook  https://www.fusotao.org/fusotao-greenbook.pdf


### Ecosystem Fit
We have implemented Fusotao protocol over substrate as a permissionless network which permits submitting proofs with zero-cost and low-latency. therefore, we could deployed our    matching verification protocol on substrate.
Our target audience includes parachain, dapp, wallet, UI developers, designers, my own user base and some dapp's userbase.
Our project meets open, reliable and fast.


### Team members

- Zhang Yu
- Jason Ching
- Daniel Wong
- Jonny Dewan

### Contact

- Contact Name: Daniel Wong
- Contact Email: daniel@fusotao.org

### Legal Structure
- Registered Legal Entity: UINB Tech Pte. Ltd.

UINB Tech
UINB is Not Blockchain. UINB Tech has 17 repositories available. Follow their code on GitHub.

### Team's experience
- Yu Zhang
Senior programmer, proficient in rust language programming. Senior expert in blockchain technology application and DeFi application. Yu Zhang has rich experience in big data parallel computing and distributed algorithm optimization, and he has in-depth research in blockchain and cryptography.
- Jason Ching
Co-founder, responsible for the operation and marketing. Five years of experience in blockchain.
In recent three years, Jason participated in the production and operation of more than 5 application chains and DeFi projects with a maximum market value of US $10 billion.
- Daniel Wong
Co-founder, Business development. Four years of blockchain operation experience. With extensive market operation experience, previously she held leadership roles in operations in multiple projects and exchanges. Daniel is fascinated by blockchain & the crypto market it has begotten.
- Jonny Dewan
Rust language experts and blockchain technology expert. Have long studied the application of blockchain technology in the financial field.
Jonny has rich experience in the technical architecture of crypto currency wallet and exchange.

### Team Code Repos

- Fusotao team:https://github.com/uinb

## Development Status :open_book:

### Fusotao Monthly Report(2021.10)
#### Fusotao Greenbook Draft Release
- Greenbook Draft v0.2.2
#### Fusotao Whisky Devnet Online
- The first open devnet Whisky now can be viewd in Polkadot explorer. wss://whisky.fusotao.org
- The web wallet extension TokenKeeper for Fusotao can be downloaded from Github. It won’t be available in Chrome/Firefox store until stable.
#### Fusotao Protocol Update
- Verification & Prove have been completed. Visit Github to see more details.
- Galois now supports self-trading prevension. Refer Github
- Merging proofs is now being WIP.
#### FXDX Testnet Online
- Online test is now available over Whisky net.
- Some tests of verification have been passed.

## Development Roadmap :nut_and_bolt:

### Overview

- **Total Estimated Duration: 7 months
- Full-Time Equivalent (FTE):  8 FTE
- Total Costs:  1,000,000 USD

### Milestone 1  —  Product development work in the early stage
We have completed all the product development work in the early stage, and the product has the conditions for launching the test network

### Milestone 2  — Bridging to Ethereum testnet

- Estimated Duration: 1 month
- FTE:  8
- Costs: 100,000 USD

| Number | Deliverable | 
| -----: | ----------- |
| 1. | Testnet launching | 
| 2. | Bridging to Ethereum testnet | 
| 3. | Proving optimization | 
| 4. | Second round of financing|  

### Milestone 3  —  Mainnet launch

- Estimated Duration: 3 month
- FTE:  8
- Costs: 100,000 USD

| Number | Deliverable | 
| -----: | ----------- |
| 1. | Bridging to NEAR | 
| 2. | Mainnet launch, a new journey | 
| 3. | Council election | 
| 4. | The first orderbook DEX online |  
| 5. | Wallet extension |  

### Milestone 4  —  Community governance

- Estimated Duration: 3 month
- FTE:  8
- Costs: 100,000 USD

| Number | Deliverable | 
| -----: | ----------- |
| 1. | Marketing sub-protocol | 
| 2. | Community governance  by staking for more DEX. Make Fusotao to become a safe, universal, and open financial infrastructure. | 


## Future Plans

There is still a lot of space for growth in the future, as our vision is "An innovition paradigm of Defi", we will design the token economics to let more people involved in the whole project to incentive the community to create more customized, such as claiming as a Matcher & Prover, becoming a Validator, voting to earn, or trading to earn rewards. Fusotao is fully open source, anyone can build decentralized finance application easily. Visit our repos on Github. After this grant is finished, everythig will be started.


## Additional Information :heavy_plus_sign:

- Official Website https://www.fusotao.org
- Fusotao Deck  https://www.fusotao.org/static/Fusotao%20deck.pdf
- Greenbook https://www.fusotao.org/fusotao-greenbook.pdf
- Whitepaper https://www.fusotao.org/fusotao-whitepaper.pdf
- Demo video https://youtu.be/NjwhsonPdHM
