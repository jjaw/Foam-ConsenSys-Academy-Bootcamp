---
tags: decentralized-trust-protocol
---
# Digital Signatures

Digital signatures use a combination of the key signing and hashing to create what we're calling **decentralized intent**.

A signature is made in blockchain when a hash of the message is signed by the private key of the account holder

Unsigned hash is formed by making a hash of `sender`, `receiver`, and `amount`. A second signed hash is formed by combining `sender`, `receiver`, `amount`, and `hash data` and signing all those fields.

![](../attachments/2022-07-05-18-56-25.png)
*(a simplified signed blockchain transaction)*

## Advantages

A message that has a valid digital signature on it provides three different confirmations: Origin, Message Integrity, and Intent.

- **Origin**: If a private key digital signature is valid then the signed message has to come from the account associated with the public key.
- **Message Integrity**: Hash proves that the message has not been tempered with by anyone else.
- **Intent**: By signing the first hash, the owner of the private key is signalling their intent to execute the commands or agreements contained in the message.

