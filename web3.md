# Web 3.0

Web 1.0: Read only
Web 2.0: Interactive - Read & Write (user create content)


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




