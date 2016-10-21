# Email discussion on difference between distributed and decentralized databases / ledgers / networks

The following is a recap of the email discussion on distributed vs decentralized dbs

### centralized - decentralized - distributed

![graphical difference](http://networkcultures.org/unlikeus/wp-content/uploads/sites/2/2013/03/networktypes.png)


- centralized db: and only has one instance : eg. a production db on AWS accessible by multiple dyno’s.
	- decentralized db: that has multiple instances holding the data, resulting in redundant duplication and potential synchronization issues. Can have data duplication for redundancy purposes. (eg. fb), but in general there is no problem in trust / consensus as there very often is only one ‘owner' accessing the data. The problem here is not consensus, rather synchronization

- distributed db: any db in which every agent has a (almost) full copy of the database. There is always data duplication in this example. eg. bitcoin, ethereum, but also private blockchains.

I thought the idea was to research both instances and come to a conclusion for each, on how blockchain could solve their issues.

Porting your definition of distributed and decentralized ledgers to our conversation, it seems to be equivalent with public vs private ledgers:

- distributed ledger ~ public ledger ("unpermissioned" blockchain): ie ethereum, bitcoin: data is publicly available, trust issues could arise

- decentralized ledger ~ private ledger (“permissioned" blockchain): an agent need permission to have access to the blockchain. This restriction can conclude only the joining of the ledger, but might also go further eg. whether an agent can join in a proof of stake bidding, whether an agent can send transactions, etc… depending on the implementation of the private blockchain. Although it seems that in a private blockchain still could have a trust issue. I’m think eg. about a consortium of banks that setup a private blockchain to share data, don’t trust each other, but certainly don’t want other actors having access to this data.

=> Think about a difference between distributed and decentralized what would happen by removing one node of the network (see the image): in decentralized case you will have other nodes being isolated from the rest of the network, in distributed case they would still be in touch with the network through other pairs. To expand on it these centers in the decentralized typology would have a private blockchain between them and would act as a gateways to the system.

### ledgers vs blockchain vs databases

The ledger is more like a table in a database.

I would say that blockchain (as a data structure) is a subset of a database.
