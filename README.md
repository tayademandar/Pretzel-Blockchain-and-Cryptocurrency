# Pretzel-Blockchain-and-Cryptocurrency

Pretzel is a fully Decentralised Blockchain which runs on multiple nodes. It has the ability to mine a block, get rewarded for a  mining a block and add transaction to a block like sending cryptocurrency to a person. This Blockchain uses proof of work.

We can send `GET` requests to the  nodes of the blockchhain to:
- retrieve information about the chain `(/get_chain)`
- mine a block `(/mine_block)`
- check validity of the chain `(/is_valid)` 
- replace the chain with the longest one when nodes are not updated `(/replace_chain)`

ALso `POST` requests can be sent to the blochckain to:
- add transaction to the block `(/add_transaction) `
- connect nodes with each other `(/connect_node)`

**Use this syntax in Postman to perform the `GET` and `POST` request on the blockchain** : 
```
http://127.0.0.1:5000/request_name
```

Every node uses diferent ports  e.g 5000, 5001, 5002 etc 
