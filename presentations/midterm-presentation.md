# Midterm Presentation

By Pelle Jacobs, June 26th, 2017

Promoted by prof. Jochen De Weerdt and supervised by Vytautas Karalevicius

---

# Small revision of focus point

- instead of focusing on decentralized data storage with blockchain systems
- more interesting 'how concept of replacing a previously thought indispensable, central entity with technology, can be applied to data storage, resulting in distributed data storage'

This allows to broaden the focus from only 'blockchain' applications, to also include 'vanilla' public key cryptography which in itself is already a strong force in replacing a middleman.

Although maybe not a huge difference, it gives me a the opportunity to have a different mental approach to the subject

---

# Table of contents

1. Prior research: defining the major concepts
2. Aim of the research: how can the idea to replace the middle man by technology be applied when dealing with distributed databases?
3. Actual proposals on how to actually merge the idea of distributed data storage

---

## Prior research: defining the major concepts

3 main concepts to discuss:

- public key encryption
- blockchain:
- the definition of a blockchain (as defined by Antonopoulos), the workings of a minimal blockchain, the characteristics of a blockchain (eg. consensus and availability)
- properties of a blockchain: the differences between blockchain: consensus mechanisms (POW and POS), access to data (private and public), power to accept transactions (permissioned and unpermissioned)
- examples of blockchains
- distributed databases:
+  difference between the terms distributed, decentralized and centralized and advantages and trade offs of using a distributed databases compared to a fully centralised database or decentralized database
+  examples of distributed networks and databases and how they achieve consensus (git, torrent, non-persistent p2p networks)

---

## Aim of the research:

Collaborative databases can face several specific challenges such as consensus issues and consistency / integrity issues. The characteristics of a blockchain could solve these issues.

Applying the main idea to collaborative databases: there are two approaches

- can this idea be applied to actually storing the data: what would this mean? What would the consequences / resulting situation be? what would the advantages be? what are some possible applications if this would be possible?
- can this idea be applied to enable interaction between databases, either to achieve consensus between versions of the same database, or in the interactions between different databases

---

## Proposals: store data onto the blockchain

Storing data onto the blockchain:

- Not feasible: storing data directly onto a blockchain, eg. onto the Bitcoin blockchain: performances issues mostly because of limited space
- Storing actual data onto Ethereum: as Ethereum allows anything, storing data is also possible
- Using an alt chain that manages distributed data storage eg. Siacoin

Coordinating consensus between databases:

- Timestamping a collaborative database onto the bitcoin blockchain
- Applied example: putting a will onto a blockchain: starting from a simple document that is signed with a private key all the way to an Ethereum program that actually publishes the document once deceased.

---

## Sources

- Published literature: Antonopoulos
- Published articles: Baran on Distributed Networks, Bitfury group on public and private blockchains and proof of work vs proof of stake
- White papers: Bitcoin, Ethereum, Siacoin, Ripple, Interledger, Dash, InstantTX
- FAQs and Wikis: Ethereum wiki, Ripple Dev Center,
