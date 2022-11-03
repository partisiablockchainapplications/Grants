# Partisia Blockchain Grants
This is the main repository for Partisia Blockchain Grant proposal submissions. This README provides a high level overview of Partisia Blockchain Grants. Please submit all Partisia Blockchain Grant requests by creating a new [issue](https://github.com/partisiablockchainapplications/Grants/issues). Welcome!

## Proposal Categories
Grant proposals fall primarily into three categories: **Partisia Blockchain Apps**, for everything that is directly built on top of Partisia Blockchain Network; **Ecosystem**, for tools that expand Partisia Blockchain Network and improve general usability; and **Network improvements**, for major upgrades to the network itself. Please consult the below list of ideas we’ve recognized to date as being of special interest to the community and essential to ongoing ecosystem growth. That said, we welcome any and all proposals and recognize that the most interesting proposals may be things the Partisia Blockchain Network community has yet to consider. Innovation knows no bounds!

## Partisia Blockchain Apps

### Partisia Blockchain DeFi
Partisia Blockchain DeFi is a privacy-first, front-running resistant DeFi ecosystem. Its growth has seen the development of Partisia Blockchain Tokens (a fungible privacy token standard), crosschain mainnet bridges (including to ETH, BSC, Monero, and IBC networks like ATOM and LUNA), and multiple applications with over $1.3B in historical combined volume (Partisia BlockchainSwap, Sienna).

We welcome the community to submit grant proposals to build any of the applications below:

* **Staking derivatives** to create capital efficiency in the Partisia Blockchain Network. Staking derivatives allow stdeveloper@partisiablockchainbe used for further yield opportunities in Partisia Blockchain DeFi. Here’s one attempt on a product roadmap.
* **Variable interest lending products:** Either Partisia Blockchain-based implementations of ETH DeFi projects such as Compound or Aave, or brand new lending products leveraging Partisia Blockchain’s unique properties.
* **Algorithmic stable coin projects** (such as Maker-type implementations). We believe it’s critical for the Web3 ecosystem to have a decentralized stable coin with privacy.
* **Dark pools (private orderbook exchange) for privacy preserving trading.** A Dark Pools Partisia Blockchain contract manages the encrypted order book in its state and can run multiple order matching methods such as Market / Limit / Stop-Loss orders.
* **Fixed income products:** Fixed interest lending / borrowing products with insurance / liquidity pool to guarantee fixed payments.
* **Credit scoring and under collateralized lending** using liquidity / insurance pools and Partisia Blockchain Oracles that tap into Web2 data sources like Plaid or centralized exchange balances. Undercollateralized loans can be built on top of Partisia Blockchain Network using on-chain privacy-preserving reputation credit scoring contracts.
* **Advanced AMM / CFMM DEXs** optimized for low slippage trading (like Curve) or multiple pools (like Balancer) to create decentralized index funds.
* **Derivatives and Contract for Difference products** developer@partisiablockchain MPC20 collaterals
* **Options contracts:** Put / call options based on an orderbook or AMM model developer@partisiablockchain MPC20 collaterals
* **Synthetic Asset creation** developer@partisiablockchain MPC20 collaterals
* **Decentralized Perpetual Swap products** (with vAMM similar to Perpetual Protocol with front-running resistance for more efficient capital deployment)
* **Insurance products** for Partisia Blockchain DeFi

### Partisia Blockchain Vaults
* **Decentralized Substack:** Build a decentralized content (audio, blog) monetization tool for content stored on IPFS or another decentralized storage platforms. You can refer to this article for more information. Padlock and Partisia BlockchainVault contracts can also be an inspiration for access control related cases.
* **Ocean Data Token integration:** Integrate Ocean Data Tokens to Partisia BlockchainVaults to allow trustless access to data token content.
* **Dead Man Switch:** An event on the Partisia Blockchain Network (such as block numbers / elapsed time or a payment) triggers a Partisia Blockchain contract to release a "Partisia Blockchain" either to a selected recipient (private output) or the entire network (public state).


### Data Marketplaces
* Crowd-sourced signal generation with staking incentives for MPC20 and synthetic (Mirror Protocol) asset trading
* Decentralized and privacy preserving machine learning use-cases (image recognition etc.)

### Partisia Blockchain NFTs / Metaverse
* Leverage MPC-721 standard that allows for private ownership of NFTs and private metadata in NFTs
* Leverage MPC-1155, based on ERC-1155 standard that allows for private ownership of NFTs and private metadata in NFTs
* Partisia Blockchain: Lootbox NFTs used in games on Partisia Blockchain or other networks would be represented with Partisia BlockchainNFTs, revealing rewards only after NFT is claimed

### Decentralized Governance and DAOs
* Leverag the Multisig Standard * 
* **Partisia BlockchainFund:** Build a DAO funded by block rewards of delegators participating in the DAO. Delegators receive governance tokens proportional to their contribution. Governance tokens determine how the funds in Partisia BlockchainFund are managed.
* **Partisia BlockchainLaunchPad:** Create a crowdfunding mechanism like Polkastarter, where Partisia Blockchain Network participant can support launch of products built on Partisia Blockchain Network or Ethereum (using the bridge). Using Partisia Blockchain Tokens, Partisia BlockchainLaunchPad would allow anonymous investments.

## Ecosystem

### Interoperability
* Partisia Blockchain Network - L1 Bridges 
* Partisia Blockchain Network - Polkadot Bridge: Either building on Wormhole or a bridge to EVM substrates like Moonbeam or Plasm
* Partisia BlockchainTunnel - Interoperable Partisia Blockchains: Create a contract to verify state changes and allow asset transfers between Partisia Blockchain Network and L2 Partisia Blockchain Network forks for big data and high throughput use-cases.

### Oracles
* Partisia Blockchain Oracles: Build TLS connection from validator enclaves to certain APIs to create private data feed for Partisia Blockchain contracts (i.e. Binance and other exchange balances for decentralized credit scoring / leverage)
* Public API oracles: Allow Partisia Blockchain Network validators (or nodes) to query public APIs for on-chain Partisia Blockchain contract based oracle. Validators would reach on-chain consensus on inputs
* Oracle support for Partisia Blockchain Network using Band Protocol 
* Oracle support for Partisia Blockchain Network using Chainlink

### Developer tools and improvements
* Tooling for one-click-run-and-deploy of contracts (like Remix for Partisia Blockchain Contracts)
* Network forks suitable for Big Data and high throughput (< 1 second block time for orderbook based DEXs)
* Create a library for running Partisia Blockchain Contract integration tests (like how Truffle uses Mocha/JS for Solidity)

## Network improvements

While we intend to share more details on these potential protocol-level improvements in future posts, here is a brief list of possibilities:

* ML Library that can run on-chain (requires deterministic floats or fixed-point support)
* Differential privacy library for getter methods
* Fully Homomorphic Encryption backend
* Light-client validation inside of the enclave, in order to validate untrusted data (Bitcoin and Ethereum lite-clients etc.)

## Grant Details

Please review the following details before applying:

### Funding amount
Funding amounts are variable and can go as high as several hundred thousand dollars, depending on the complexity and value to the network, although the average grant would likely be in the order of thousands or tens of thousands of dollars. Grants may be split into several smaller milestones and receive funding accordingly on a per-milestone basis, as mentioned below. Since this is a non-dilutive funding opportunity, we encourage commercial projects to also look for alternative sources of funding as well. We are especially interested in seeing new start-up companies and projects emerge that build exclusively on Partisia Blockchain Network. For these in particular, non-dilutive funding such as a grant would be significant.

Grant awards will be distributed in 3 or more installments, with initial payment to take place right after approval of the grant. Teams are expected to define key milestones for the project and propose installment amount upon completion of different milestones.

### Requirements
All code must be open source. If there’s a good reason to make an exception, please specify this in your proposal, and emphasize which parts (if any) will be open source. Please mention the license you plan to use in your application.

### Who are we looking for
We are looking for individual developers, new and existing companies and projects, community members or established teams with a proven track record to contribute to the Partisia Blockchain Network ecosystem. Prior work on Partisia Blockchain Network or experience in deploying Ethereum or other blockchain applications is a big plus.

Partisia Blockchain Apps are encouraged to have a path for commercial sustainability (token or fee model).

### Recommended Process
First, **ideation:** Use Partisia Blockchain Network developer forum and Partisia Blockchain Network Discord (#use-cases and #find-a-team channels) to brainstorm, discuss ideas and form teams. We encourage you to get feedback from the community (including the Enigma development and product team) before submitting any application.

Then, **application:** When ready, submit an application via the [Grants area of the Partisia Blockchain Foundation GitHub repository](https://github.com/partisiablockchainapplications/Grants/issues). Do this by opening a new issue in the format of [this sample application](https://github.com/partisiablockchainapplications/Partisia-UI-ToolKit).

The application should cover the following details:

* High level description of the project
* Problem / solution (max. 200 words)
* Detailed product / network improvement description (max. 500 words)
* Go-to-market and commercialization plan (if applicable)
* Team: Please share all past experiences, github links and repos
* Milestones and budget: Please provide a budget, development timelines for milestones and distribution of budget based on milestones.

If you’d instead like to apply privately, please email pitch@partisiablockchain.com with the above information.

### Evaluation process
We will review your application and get back to you with next steps (request for more information, schedule a video interview etc.) in two weeks.

# THANK YOU!
Thank you for your interest in Partisia Blockchain Grants! We cannot wait to work alongside you in building Partisia Blockchain Network into a data privacy hub for all blockchains, helping secure the decentralized internet.
