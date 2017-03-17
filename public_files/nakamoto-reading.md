# Bitcoin paper - Nakamoto

## 1. intro
deals with several problems of trust based systems

## 2. transactions

electric coin = chain of digital signatures
to avoid double spending => need to know all the transactions ever

## 3. time server
creates chain: needs to be distributed somehow: proof of work

## 4. proof of work 
this proof of work = scanning for a value that once hashed begins with x zero bits. x higher, more difficult
=> once hashed, block contents cannot change duh. 

to steer average amount of blocks per hours => increase / decrease difficulty accordingly => less interest in running nodes, the proof of work will become easier
! advantage of less blocks: total size of the blockchain (# transactions in block don't matter) 

## 5. network
= specific steps to running network

## 6. incentive: 
- additional transaction to the block creating node, granting x bitcoin
- transaction fee, by taking a bit of the input value of all the transactions

## 7. disk space 
sth with merkel trees? 

## 8. verification
- run your own node
- let the network verify and accept if longest chain has your transaction

## 9. splitting value
multiple ins (combining value) and outs (splitting value) in transaction

## 10. privacy
- public keys are public (duh) but anonymous
- to be able to use a received transaction, need to have the private key connected to the receiving public key => once all full outs of a transaction is used, private key is not longer useful (right, right?) 

