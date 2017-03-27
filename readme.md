# Master Thesis Pelle Jacobs

## Paper structure

1. What is blockchain
  - [ ] pure definition: C7 from 'mastering bitcoin'
    - [x] monetary and non-monetary transactions:
      - [ ] monetary is straightforward simple bitcoin
      - [ ] non-monetary: ???? no readings yet 😒
  - [ ] Characteristics of blockchains
    - [ ] private vs public blockchain:
      - [ ] public: just a description of the general bitcoin blockchain: C7 from 'mastering bitcoin'
      - [ ] private: ??? => no examples yet of private blockchains
    - [ ] permissioned vs unpermissioned: ?? what is exactly the difference with public / private? (=> joining vs not allowed to join)
    - [ ] proof of work vs proof of stake:
      - [ ] proof of work: easy description of bitcoin mining: Nakamoto paper
      - [ ] proof of stake: (dash masternodes instant send => absolutely not related), ethereum FAQ
      - [ ] proof of storage: maybe?
    - [ ] smart contracts => ?? related to non-monetary transactions?
  - [ ] advantages of having a collaborative database on a blockchain: Nakamoto paper touches this briefly in the introduction => instead of advantages, talk about why blockchain has been developed 
  - [ ] different implementations of blockchains: compare bitcoin blockchain with ethereum (for public blockchains), private blockchains?  ???

2. What are distributed and decentralised databases
  - [ ] 'distributed' and 'decentralised' as concepts and usefulness: Baran paper
  - [ ] common distributed / decentralised databases => cassandra?
  - [ ] applications of these databases => facebook?

3. Evaluation flowchart (actually no flowchart) => more evaluation instead
  - advantages and disadvantages of to use for distributed databases
  - 4 ways of actually applying bc to dbdb
      - open ledger (nothing? really weird)
      - blockchain hash storing
      - ethereum direct storage
      - que mas? (IPFS, filecoin (not really in development anymore though), )

## Reading list:

### books / papers

**bitcoin / blockchain**

- [x] S. Nakamoto, "Bitcoin: A Peer-to-Peer Electronic Cash System", 2008
- [ ] A. M. Antonopoulos, "Mastering Bitcoin", 2015:
  - [x] C7: Blockchain
  - [x] c5: transactions
  - [x] c8: mining
  - [x] c9: alternative coins
- [x] ethereum white paper
- [x] research on openbazaar, etc
- [x] dash whitepaper and instant send white paper

**collaborative dbs**

- [x] P. Baran, "On Distributed Communication Networks", 1964 => rather specialized on warfare, not much theory on database systems, but rather the concepts of decentralized, centralized and distributed

### webmaterial

**blockchain**

- [ ] http://www.multichain.com/blog/2015/11/avoiding-pointless-blockchain-project/ "How to determine if you’ve found a real blockchain use case"
- [ ] (B. Suichies, "Why Blockchain must die in 2016", 2015)

also interesting:

- other posts at http://www.multichain.com/blog/category/private-blockchains/
