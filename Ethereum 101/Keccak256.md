# 29 - [[Keccak256]]

Ethereum uses Keccak256 as its cryptographic hash function. Keccak256 was the winning candidate for the SHA3 competition held by NIST but is different from the finally adopted [[SHA3]] standard.

---
## Slide Text
- Cryptographic Hashing Function
- Derived from SHA3 Competition (NIST-2015)
- But different from the final SHA3 standard
- Core fundamental primitive 


---
## Code Examples
Get the Keccak256 hash for the value: `ethereum_string`
```
# seth keccak ethereum_string
0x6c06391f47c23c74cc0d45831681e32e8403e6f67ca339ce4eb290944a252ca3
```
---
## References
- [Ethereum Book: Chapter 4 - Keys & Addresses](https://github.com/ethereumbook/ethereumbook/blob/develop/04keys-addresses.asciidoc)