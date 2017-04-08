# Ripple Research

## Ripple white paper

### prior research

3 main problems with distributed (payment) networks: 

- correctness
- agreement (doublespending and resulting forks)
- utility: usefulness  

2 types of failures: 

- standard failures: a node is killed
- Byzantine failures: a node has malicious intentions

definition of consensus: 3 conditions: finite decision making, same decision, both values to agree upon are possible a priori

to measure consensus algorithm: fraction of faulty processes it can tolerate

### ripple protocol

Works in rounds: 

1. collect valid transactions
2. push transactions to other nodes in the Unique Node List and vote on other nodes' transactions
3. if 80% agrees on a transaction: accept the transaction in the ledger

two conditions for this to work: 

- #faulty nodes ≤ 20%, otherwise correct transactions can be rejected (= strong correctness), if #faulty nodes ≥ 80%: possible that incorrect transactions are accepted
- specific connectivity formula, to ensure no forks happen in the network


### Personal Concerns

- some aspects are not completely clear, eg the connectivity formula
- it seems that there is still need for a central entity to monitor the global network and the UNLs of users 


## Ripple dev center

### ledger consensus process

- consensus process is actually an iterative process of continuously sending out the transactions you agree on to your UNL