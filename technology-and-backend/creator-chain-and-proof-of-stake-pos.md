# Creator Chain and Proof of Stake (PoS)

## Blockchain Technology

Mesi’s infrastructure is designed to operate on a high-performance blockchain environment that ensures scalability, cost-efficiency, and robust developer support. Rather than building a proprietary consensus layer from inception, Mesi will leverage an established Layer 1 or Layer 2 network whose technical and ecosystem characteristics best align with the platform’s needs.

Key considerations guiding the selection include transaction throughput and finality, cost structure, smart contract flexibility, maturity of development tools, wallet interoperability, and the broader ecosystem’s liquidity and user base. This approach enables Mesi to prioritize product innovation and user experience while relying on a proven and secure base layer.

## Proof of Stake and Validator Architecture&#x20;

Proof of Stake (PoS) is the consensus mechanism underlying most modern blockchain networks. Validators are selected to create blocks based on the amount of cryptocurrency they stake as collateral. This economic model aligns validator incentives with network security, as dishonest behavior results in loss of staked assets.

PoS networks maintain security through distributed validation—independent operators collectively validate transactions, propose blocks, and reach consensus on chain state. Validators earn rewards through transaction fees and protocol token issuance. This architecture requires substantially less energy than alternative consensus mechanisms.

Initially, Mesi will deploy smart contracts on an established PoS blockchain, inheriting security from that network's validator set.

## Node Operator Program and Decentralization Stages

As the platform matures, Mesi will introduce node operators who stake a defined amount of $MESI tokens to participate in infrastructure operation. Node operators will be progressively entrusted with operating Mesi's infrastructure through the following transition stages:

**Stage 1:** Decentralization of application layer (off-chain infrastructure)

**Stage 2**: Decentralization of the indexing layer (bridge between off-chain and on-chain)

**Stage 3**: Decentralization of settlement layer (on-chain infrastructure) - once the Mesi native blockchain is developed.&#x20;

Each stage will be preceded by the development of native infrastructure for that specific layer. In exchange for their participation and staked capital, node operators will earn rewards. The particular structure and timeline for this program will be determined based on platform scaling requirements and infrastructure maturity.

## System Architecture

Mesi's infrastructure consists of four layers:

<figure><img src="../.gitbook/assets/Blockchain.png" alt="" width="375"><figcaption></figcaption></figure>

## Settlement Layer (Blockchain)

The settlement layer consists of smart contracts on the selected PoS blockchain. This layer stores:

* Wallet addresses and authentication credentials
* NFT metadata for content ownership (token IDs, creator addresses, timestamps)
* $MESI token balances and transaction records
* Aggregated records of user interactions (with each other and with the platform)&#x20;
* Governance functionalities and data records

The settlement layer does not store media files, full-text content, social engagement metrics, or real-time interaction data due to on-chain storage costs.

## Application Layer (Off-Chain)

The application layer handles computational and storage requirements:

* Relational databases for user profiles, social graphs, and content metadata
* Object storage for media files
* API services for business logic
* Notification systems
* Analytics infrastructure

This layer operates off-chain because response times must be measured in milliseconds rather than the seconds required for blockchain consensus.

## Indexing Layer (Bridge)

The indexing layer synchronizes blockchain state with the application database. This middleware monitors the blockchain for Mesi-related events (NFT mints, token transfers, ownership changes) and updates the application database accordingly.

Implementation options include decentralized indexing protocols or managed API services. When a creator mints a content NFT, the indexer detects the blockchain event and updates the application database within seconds.

## Accessibility Layer (User Experience)

The accessibility layer encompasses user-facing interfaces:

* Web and mobile applications
* Account creation and authentication flows
* Payment interfaces
* Content management tools

This layer operates off-chain and under centralized control.

## Gasless Transactions and Account Abstraction

Mesi allows users to interact with the platform without dealing with crypto wallets, gas fees, or blockchain details unless they want to.

Each user automatically gets a smart contract wallet when they sign up. They can log in using a Google or Apple account or connect their existing crypto wallet.

For normal actions like posting, minting NFTs, or receiving tips, Mesi covers gas fees up to a monthly limit, so the user does not have to spend any blockchain currency for interactions or approve any activities at the wallet level.&#x20;

Once that limit is reached, users can either pay fees with $MESI tokens (automatically converted to the network’s gas currency) or switch to full self-custody and handle gas payments themselves.

## Content Ownership and Storage

Media files are stored in a cloud infrastructure optimized for global delivery. Ownership and provenance are recorded on-chain.

Upload Process:

1. User submits media through the application
2. Content files are kept in a scalable storage system and made available to users via a global network of delivery servers
3. A cryptographic hash is computed for the file content
4. NFT is minted on-chain with metadata: hash, creator address, timestamp, licensing terms
5. NFT ownership is transferred to the creator's wallet

The NFT metadata includes creator information, a cryptographic hash of content, storage location reference, creation timestamp, licensing terms, and more. This enables verification that a specific creator produced specific content at a specific time.

**Content Removal:**

Users can delete their media files, hide them from the platform, and block others from accessing them — except in certain cases (for example, legal requirements or users who already paid for lifetime access).

However, the NFT record on the blockchain and its cryptographic hash remain permanent. This keeps a verifiable record of when and by whom the content was created, without exposing the content itself - even if the file itself is no longer available.

All personal data is stored off the blockchain and can be fully deleted to meet privacy laws. The blockchain only keeps anonymous information like wallet addresses and file hashes.

## Decentralization Roadmap

**Phase 1:** Centralized Operations

Initial launch operates under centralized control. Mesi manages infrastructure, sponsors transaction fees, stores content on commercial platforms, and maintains administrative control over smart contracts. This enables rapid iteration and immediate fixes.

**Phase 2:** Progressive Decentralization

As the platform demonstrates stability, specific components transition to distributed operation. Storage infrastructure may migrate to decentralized networks pending performance and economic evaluation. Smart contract governance transitions from individual administrative keys to multi-signature schemes, eventually moving toward community governance. The node operator program launches, enabling community members who stake $MESI to co-create decentralized infrastructure and participate in its decentralized governance.

**Phase 3:** Distributed Operation

Long-term decentralization goals include distributed content storage, community-operated indexing infrastructure, and token-holder governance.

## Transparency & Zero-knowledge proofs

Blockchain data, such as wallet addresses, NFT ownership records, transaction history, and token balances, is publicly visible, ensuring full transparency and verifiable ownership.

Personal information—such as user identities, media files, social connections, and engagement data—is stored off-chain under strict privacy and security controls.

Mesi implements zero-knowledge technologies to protect user privacy, allowing verification of ownership and credentials without revealing identity or exposing underlying data.

\
\
\
\
\
<br>
