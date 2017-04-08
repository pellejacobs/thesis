# interledger white paper

## interledger payments

use of connectors to cross several ledgers to exec a payment

to ensure every participant (ie connectors and recipient) gets paid, use of escrows on the all the ledgers

## atomic interledger payments

use of notaries that evaluate whether a signed_receipt is valid and send all the participants to either execute the escrow, or abort the escrow and return the funds 

=> to be able to exec an escrow assigned to your wallet, you need the signature of the notaries, to abort you don't any signature

## universal interledger payments

once entire payment chain is setup and all funds are in escrow, the recipient can exec his payment by providing the signed_receipt => execs a waterfall that enables all the connectors to in turn execute their escrow 

=> has different risks, so also different rewards