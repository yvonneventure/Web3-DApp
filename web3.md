# Web 3.0

- Web 1.0: Read only
- Web 2.0: Interactive - Read & Write (user create content)


<img width="732" alt="Screen Shot 2022-10-11 at 11 12 12" src="https://user-images.githubusercontent.com/103771536/195130315-385c80d1-1795-4c93-813a-537fcfa767ef.png">


## How Does Blockchain work?

Blockchain is a distributed(decentralized) ledger where each information/block is encrypted(hashed) and depended on the previous block(chained) so that the history of the informatio is immutable. It also holds integrity as the ledger is distributed, so even one chain is modified, other chains will have the same information (hashes) stored, so that they can tell the bad player.

### 1. What's a block?

There are requirements need to be satisfied to build a block.

<img width="798" alt="Screen Shot 2022-10-11 at 11 35 25" src="https://user-images.githubusercontent.com/103771536/195136118-0552f536-915d-4a14-9f6e-909241d4284b.png">

1. The hash created/mined needs to start with how many 0s(difficaulty).
2. The `Nonce` is the part to be mined/caculated by the computer to make the nounce and information inputted and previous hash together to create a hash that starts with four 0s in this case.
3. Once mined and meet the requirements, the block is valid and the information inputted can no longer changed.
4. If `Nonce`, the information or the previous hash, any of them changed the end hash will changed and need to mine/calculate again.

So basically use `Nonce`, information and previous hash to create a hash.

### 2. How to chain them together?

The hash in each block is depending on previous hash, that's how they chained together. The end hash of the previous block will be used to created the current block. 

<img width="439" alt="Screen Shot 2022-10-11 at 11 41 48" src="https://user-images.githubusercontent.com/103771536/195137980-203d1969-8309-40d7-9b16-ca2964447fe8.png">

### 3. How to hold integrity by distributing it?


Let's say we have 2 more peers(miners), each of them will have a copy of the current blockchain(the entire chain). If peer A changed information in it's chain, eventhough the information can be a valid block (by re-mining the whole chain from the start), since other peers have a copy, the system will know that peer A is a bad player, because both peer B and peer C(more than 50% of the players) has the same records but peer A's records don't match with them.


<img width="525" alt="Screen Shot 2022-10-11 at 11 46 07" src="https://user-images.githubusercontent.com/103771536/195138653-3ef19ceb-c3c3-40ca-8c0b-3ce76e0fe6cd.png">

### Smart Contract

The data field doesn't need to be text or transaction, it can also be a code block.

For example, company A will pay company B x dollar for the service company B delivered. Once company B delivered it, the code can execute itself and company B get paid automatically.





