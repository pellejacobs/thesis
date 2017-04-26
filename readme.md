# Master Thesis Pelle Jacobs


## Last paper structure

1. introduction: general question (something like "How to apply blockchain technology and other innovations behind cryptocurrencies to enable distributed databases?") and reading guide.
2. "prior research" (needs better title, maybe something like "setting the scene"): 
    - innovation of bitcoin: replace middleman with technology, specifically for bitcoin this is the blockchain:
        - public-private key cryptography: public-private key cryptography is central to understand the innovations bitcoin uses to revolutionise
        - definition of blockchain: carefully explain every aspect of the definition as provided by Antonopoulos
        - Extra chapter: how does a minimal blockchain work? which interesting characteristics are created? 
        - ~~characteristics~~ properties of blockchains:
            - in intro: start out with the specific advantages that a blockchain provide
            - consensus mechanisms for blockchains: proof of work, proof of stake,
            - who can access the data: private or public
            - who is allowed to accept new transactions: permissioned or unpermissioned
        - different implementations of blockchains (bitcoin and ethereum) and applications on top of blockchains (ie. colored coins, merged mining and namecoin, anchoring, sth else?)
    - distributed databases:
        - difference between the terms distributed, decentralized and centralized
        - advantages and trade offs of using a distributed databases compared to a fully centralised db or decentralized db
    - examples of distributed networks and databases and how they achieve consensus: 
        + torrents: easy: only one version of the data is ever shared, never updated
        + git: use of master branch and "data edit powers" to update merge conflicts (= consensus issues)
        + ~~cassandra: I think this might be an interesting use case as it is also a mesh of nodes try to achieve consensus / synchronise between each other~~ (on second notice => leave this one out: this is an example of a DECENTRALISED DB)
        + distributed peer to peer networks such as the internet and open bazaar: nothing is stored, no persistence,
3. aim of the research: how can the idea to replace the middle man by technology be applied when dealing with distributed databases?
    - can this idea be applied to actually storing the data: what would this mean? What would the consequences / resulting situation be? what would the advantages be? what are some possible applications if this would be possible? 
    - can this idea be applied to enable interaction between databases, either to achieve consensus between versions of the same database, or in the interactions between different databases (_are we still talking about distributed databases in this last case?_)
4. literature review (_I feel like the entire second chapter was a literature review, and this need another more relevant title_)
    - ethereum allows storage onto its blockchain, anything else
    - timestamping onto the bitcoin blockchain, interledger system of using private-public key crypto to enable interaction (_I'm not 100% about this, as I don't understand the entire interledger thing yet_) _I feel like cassandra might come in here, as it also allows the middle man / central database to be removed, we are not talking about consensus though, and rather about synchronisation_
5. conclusion (hypothesis right now): yes, it is possible to apply this idea to distributed databases, although we are not limited to only using blockchains, as other use techs work better in other situations



## First Paper structure

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
