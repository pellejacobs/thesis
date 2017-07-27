# Properties of blockchains

sources: 

- public vs private by bitfury group (private vs public, and permissioned vs private)
- pos vs pow by bitfury? (NOT YET READ) (pos and pow)
- pos at ethereum faq (pos part)
- bitcoin whitepaper by nakamoto (pow part)

intro: 

- the blockchain concept has certain characteristics making it very interesting in specific use cases: eg. immutability, security and absence of single point of failure _not necessarily relevant to this chapter, can be left out_
- however, not every implementation of the blockchain concept is exactly the same: the blockchain developer has to make several choices to adjust his blockchain to the specific use case 

## Securing the immutability of block headers: proof of work and proof of stake

### proof of work

~todo~

### proof of stake

~todo~

## Access to the blockchain data: 

As said by the Bitfury group in () There are three levels of access to the blockchain: 

- reading the data from the blockchain
- proposing new transactions to the blockchain
- creating new blocks of transactions and adding them to the blockchain

### read access and transaction submission: private and public

- the first two access levels are intertwined and will be discussed together
- need for choice concerning read access to the blockchain data and on access to submit transactions to the blockchain : (paraphrased definitions from public vs private pt 1)
    + public blockchain: there are no restrictions nor on reading the data or submitting transactions
    + private: only a predefined list of entities can directly access the data and submit transactions
- although private bc may seem more secure because of controlled access, several of the advantages of using a blockchain are lost: (paraphrase from public vs private pt1)
    + as several clients do not have direct access to the blockchain data, they have to rely on a node that has direct access. => works against the decentralisation blockchains as there is only a limited amount of possible nodes to connect to
    + as clients now need to connect to a node with full access, not only do they need to trust this node, this interaction becomes a vulnerability => eg. a man in the middle attack becomes possible when a user wants to interact with the blockchain, a malicious party could intercept this communication and reply with false information _maybe add more info on what a man in the middle attack is_
    + only a limited set of computers has access to the transactions, opening up the risk of a human factor intervening in the blockchain operation => circumvents the reliance of the algorithmically enforces rules of blockchains
- Data on public blockchains can still be encrypted, providing suffucient security in most cases.

### access to transaction processing: permissioned and permissionless

- for the third level, the developer has to chose who is allowed to process transactions so they get incorporated into the blockchain:
    + permissionless: there are no restrictions on the identities of transaction processors
    + permissioned: only a predefined list of entities can process transactions
- 
- of course, private blockchain that only provides read access to only a certain amount of entities, will always be permissioned


### conclusion

in well regulated sectors, it might be interesting to opt for a permissioned blockchain instead of a permissionless blockchain. However, making the blockchain completely private endangers the security of the blockchain and therefore the credibility of this blockchain interpretation.
