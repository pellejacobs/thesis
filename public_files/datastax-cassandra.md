# Datastax Cassandra paper

 main features of cassandra: 

 - massive scalability
 - "never go down"
 - high performance

architecture: 

- peer-to-peer distributed nodes 
- data can be duplicated over the entire network => no node holds all the data: duplication count can be arbitrarily chosen
- if node needs to READ data: assemble all data by contacting the other nodes
- to WRITE a transaction: first written to commit log etc etc


