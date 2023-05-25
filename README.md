# Bizk-docs 

## Introduction

    Bizk aims to involve zero-knowledge prove to resolve exist problems in bitcoin ecosystem, such as centralized brc20/brc721, security loss.

    Include a set of Bitcoin zk-rollup protocol, like zkOridinals(BRC20), zkNFT(BRC721)...
    
    and also build zk a layer2 blockchain.

    the vision is prove zk proof on bitcoin blockchain directly , probably with state-of-the-art recursive aggreagtion prove system.


## 2. Problems

### Centralized Oridinals 

    Many utxo transactions in 1 block.
    Many inscrible, like brc20 json, in 1 block
    ```json
    ```
    How to prove ownership :  map the utxo to inscrible(json)
    Ordinals record the mapping in it's centralized server


## 3. How we solve it   

### Zero knowledge proof

    Bitcoin is designed for transfer utxo with simple op , turing-complete. so there is no way to run complicate computation/smart contract. However, state-of-the-art recursive aggregation zk proof system(plonky2, gsnark..) reduce the complexicity of verify proof. Let's say, if the verify could be reduce to sha256(msg) == hash, then the proof can be verify with bitcoin sha256 op.


### ZK Oridinals Protocol

    // prove owner of utxo is the owner of brc20

### Modular Blockchain

    DA : BTC
    Settle : Layer2 --> BTC ?
    Execution : Layer2, bitcoin do not support complicate operations
    Consesus : Layer2 --> BTC ?


## Roadmap:

    zkOrdinal protocol : 
    zk layer2 : security on Layer2 consesus
    prove zkp on Bitcoin : security on Bitmain, recursive aggregation zkp 