# Dash white paper
https://github.com/dashpay/dash/wiki/Whitepaper

unclear: throughout the paper, the word "quorum" used, however, it is absolutely not clear what exactly is meant by this. 

Seems to be proposing several improvements on the bitcoin protocol, most importantly by adding a "two-tier" incentivization: instead of only rewarding the miners for their work, also reward the full nodes

it is claimed this has a wide range in advantages: 

- better privacy with sth called private send, which is just an advanced coinjoin
- enables instant send somehow see further
- there is a soft limit on active full nodes, protecting the network

besides, also uses different hashing algorithm for proof of work, which is currently best solved by CPUs instead of ASICs

## Instant send white paper

the masternode system allows for near instant transactions, by enabling sth called "transaction locks":

once a instant send is propagated through the network, somehow 10 masternodes are chosen to vote on whether this transaction is valid. Once they all reach a consensus (unanimously) that this transaction is valid, it is locked and the receiver of the transaction can be sure it will be incorporated into the blockchain. 

once locked, the inputs in that transaction cannot be spend again, as they will be rejected by the network. 

or sth like that.

## final conclusion

although all really interesting, there is nothing in here suggesting anything besides the proof of work concept. 

the masternodes concept and instant send are interesting tho