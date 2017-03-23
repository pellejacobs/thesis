# Masternig bitcoin

## C7: blockchain
touches on two concepts:

- block headers
- merkel trees for transactions

## C5 Transactions

- transaction lifecycle: creation, signature, propagation and validation, inclusion in block
- transaction outputs and inputs
- chaining => less important?
- scripting language:
  - P2PKH
  - P2PK
  - multi signature
  - OP_return
  - P2SH

## C8 mining and consensus

4 steps:
- aggregating transactions
- mining:
  - coinbase transaction
  - block header
  - difficulty target
- validation blocks
- finding chain with most cumulative proof of work (=> probably longest chain)
  - forks

pools:
  - managed
  - P2Pool
=> consensus attacks
