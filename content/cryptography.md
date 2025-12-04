---
title: Cryptography
created: 2025-12-04, 12:33:20
modified: 2025-12-04, 15:46:22
---

[Julia Crypto](https://github.com/JuliaCrypto) organization.

- [Wikipedia: Cryptography](https://en.wikipedia.org/wiki/Cryptography)
- [Wikipedia: checksums](https://en.wikipedia.org/wiki/Checksum)

---

- [MbedTLS.jl](https://github.com/JuliaLang/MbedTLS.jl) : Wrapper around [mbedtls](https://tls.mbed.org/).
- [RNGTest.jl](https://github.com/JuliaRandom/RNGTest.jl) : A package that is a Julia interface to the test suite TestU01 of Pierre l'Ecuyer to test random numbers.
- [ECC.jl](https://gitlab.com/braneproject/ECC.jl) : Elliptic Curve Cryptography in Julia (secp256k1 curve).
- [OpenSSL.jl](https://github.com/JuliaWeb/OpenSSL.jl): [OpenSSL](https://www.openssl.org/) Julia bindings.

## Homomorphic encryption

[Wikipedia: Homomorphic encryption](https://en.wikipedia.org/wiki/Homomorphic_encryption)

- [SecureArithmetic.jl](https://github.com/hpsc-lab/SecureArithmetic.jl) : Secure arithmetic operations using fully homomorphic encryption.
- [OpenFHE.jl](https://github.com/hpsc-lab/OpenFHE.jl) : Fully homomorphic encryption in Julia using [OpenFHE](https://github.com/openfheorg/openfhe-development).

## Checksum

- [MD5.jl](https://github.com/JuliaCrypto/MD5.jl) : A pure Julia MD5 implementation. Honestly, just use SHA-256 for everything you would use MD5 for. MD5 is not secure, and it's not faster, and it doesn't have much going for it.
- [Nettle.jl](https://github.com/JuliaCrypto/Nettle.jl) : is a simple wrapper around libnettle, a cryptographic library, providing MD5, SHA1, SHA2 hashing and HMAC functionality, as well as AES encryption/decryption
- [SEAL.jl](https://github.com/JuliaCrypto/SEAL.jl) : wrapping the Microsoft SEAL library for homomorphic encryption
- [SHA.jl](https://github.com/JuliaCrypto/SHA.jl) : a performant, 100% native-julia SHA-1, SHA-2 224, 256, 384 and 512, and SHA-3 224, 256, 384 and 512 functions.
- [CRC32.jl](https://github.com/JuliaIO/CRC32.jl) : computing the [CRC-32 checksum](https://en.wikipedia.org/wiki/Cyclic_redundancy_check).

### Cryptocurrency

- [LearnBlockChain](https://github.com/Julia-Blockchain/LearnBlockChain) : Block chain [tutorial](https://www.youtube.com/watch?v=eDELq53TpNc) in Julia.
- [Web3.jl](https://github.com/lambda-mechanics/Web3.jl): A module for Ethereum connectivity. Parse ABI files, encode/decode ABI data, and make Ethereum [JSON-RPC](https://github.com/ethereum/wiki/wiki/JSON-RPC) calls: low-level calls, smart contract function calls and transactions.