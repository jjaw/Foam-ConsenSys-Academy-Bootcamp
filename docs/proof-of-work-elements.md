---
tags: distributed-network,
consensus-protocols, decentralized-trust-protocol, proof-of-work
---
# Proof of Work (Elements)

[[proof-of-work]]

## Messages

The fundamental message in Proof of Work consensus is **transaction**, constructed using public key cryptography and digital signatures.

Transactions in Proof of Work consensus are atomic, the network either accepts or rejects the transaction.

## Nodes

The different nodes and their roles are: Miners, Full Nodes, Light Nodes, and Archive Nodes.

### Miners

[[Miners]] solve proof-of-work puzzle in order to maintain the integrity of the network. They certify which transactions are valid by including them in blocks. When a miner creates a valid block and propagates it throughout the network, the network state is advanced in a trustless way.

[[Full Nodes]] The general network nodes which are creating transactions and passing along transactions created by other nodes. Full nodes maintain full network state and check the work of a block to ensure its validity. 

[[Light Nodes]] Network nodes which are simply submitting transactions to the network and waiting for them to be accepted by the network. They do not pass along messages nor check the validity of the network state.

[[Archive Nodes]] Maintains and provides the current state, but also maintains and provides historical states. e.g. balance at x date.

## Periods

### Period of Block Production

The period in which Miner nodes validate transactions. It begins when the miner receives the latest valid block and stops when the miner solves their Proof of Work puzzle or when it receives a valid block from another miner.

### Period of Block Propagation

This is the period in which a valid block gradually moves through the network. A full node or miner node will only propagate blocks that are valid, so the process of the network accepting a valid block (and accepted the new network state) is an emergent one.
