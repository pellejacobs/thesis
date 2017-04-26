# Blockchain definition

sources: 

- antonopoulos book
- abelson paper on data structures

to do: 

- need for different interpretations of 'blockchain' with reference in the intro

## intro
- _why we need to properly define the concept of blockchain_: as the concept of blockchain does not **mean the same for everyone** , it is important to properly define to avoid further confusion
- _literaly the definition:_ The blockchain data structure is an ordered, back-linked list of blocks and transactions.'' (p. 159). There are several aspects in this definition that need further explanation.

## back-linked list as data structure
- _start out with definition of data structure_: ``A specialised format for organising and storing data'' \cite{data-structure}. There are several types of data structures such as arrays, lists, graphs, trees, etc.
- Antonopolous defines the blockchain as special data structure as an 'ordered, back-linked list': 
- data structure that combines a number of ordered values (ref. abelson) =>  list, Ordered aspect of antonopoulos' defintion is superfluous as every list is ordered, combination of unordered values is called a set.
- to preserve order, blockchain uses back-linking: every value references the previous value
- specifically for blockchain: every block, contains the hash of the previous block in its header

## transactions

- _definition of transaction from Antonopoulos_:``data structures that encode the transfer of value between participants in the bitcoin system'' (p. 109): although mostly true, transactions can also store data. eg. Bitcoin blockchain allows for storage transactions, besides its value transactions
- there are two types of transactions: value transactions and storage transactions. Value transaction: there is a transfer of value (eg. bitcoin) between participants. It must be noted that this does not have to be an instant transfer. Several blockchain protocols allow for a custom conditions to be scripted into the transaction.
- storage transactions: store data onto the blockchain. An example of a common used non-monetary transaction is the encoding of a document on the blockchain. 
- transactions are the reason of existence for a blockchain: the blockchain exists to be able to validate these transactions, propagate them over a network and add them to a distributed ledger

## Blocks
_definition by A._: ``a container data structure that aggregates transactions for inclusion in the public ledger, the blockchain.'' (p. 160). A block is literally a wrapper for multiple transactions to make it possible for them to be included into the blockchain. These blocks then form the ordered values of the back-linked list addressed in the beginning of this section, each linking to the previous block in the list.

## conclusion
the blockchain is a list of blocks, with each block containing several transactions.

