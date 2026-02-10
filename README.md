# 2021

Monorepo for my 2021 projects. Where it all started: learning cryptography and blockchain fundamentals from scratch.

## ⭐ ecdsa-exchange

A client-server exchange that uses real ECDSA cryptography for transaction authentication. The server generates secp256k1 key pairs and Ethereum-style addresses (SHA-256 hashed, last 40 chars). The client signs messages with a private key, and the server recovers the public key from the signature to verify ownership before transferring funds. Built as part of the Oxbridge ChainShot Ethereum Bootcamp.

**Stack:** JavaScript · Node.js · Express · elliptic (secp256k1) · crypto-js

→ [browse code](./ecdsa-exchange)

## ⭐ merkle-trees

My first-ever implementation of Merkle trees, built from scratch with no libraries, just string concatenation as a hash function. Handles power-of-two and odd-numbered leaf sets by recursively splitting into balanced subtrees and hashing forward. Lots of `console.log`s and `ba dum tss` jokes. Pure learning, zero polish, exactly as it should be.

**Stack:** JavaScript

→ [browse code](./merkle-trees)
