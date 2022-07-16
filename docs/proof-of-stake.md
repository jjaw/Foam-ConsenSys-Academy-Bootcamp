---
tags: distributed-network,consensus-protocols, decentralized-trust-protocol, proof-of-stake
---
# Proof of Stake
In Proof of Stake consensus protocol, validators commit stake to validate blocks into existence.

## Validators
Participants on the network that run validator nodes to propose and attest blocks on a Proof of Stake network. Validators stake cryptos on the network to make themselves available to be randomly selected to propose a block. Other validators then validate (attest) that they have seen the block. Validators receive rewards for proposing blocks and for making attestations about blocks that they have seen. The block is added to the blockchain when a sufficient number of attestations for the block has been collected.

## Crypto-Economic Incentives
The core incentive boils down to the requirement that validators stake their own money on the network. Validators on Proof of Stake chains are forced to directly deposit a significant monetary amount onto the network.

### Incentives
Validators accrue rewards for making blocks and attestations when it is their turn to do so.

### Penalty
- Offline / Irresponsible: Validators are penalized for not following through with their responsibilities when it is their turn to do so. **Mild penalty**, if a validator is participating correctly more than half the time then her rewards will be net positive.  
- Malicious / Attack: A different penalty mechanism kicks in when a validator attempts to attack or compromise the blockchain by trying to propose a new set of data history. **Sever penalty**, large amount of the stake will be slashed.