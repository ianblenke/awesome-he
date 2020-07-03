# Awesome Homomorphic Encryption [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)


> A curated list of amazing Homomorphic Encryption libraries, software and resources.


## Contents

- [Libraries](#libraries)
- [Software](#software)
- [Databases](#databases)
- [Resources](#resources)
- [Papers](#Papers)

## Libraries

Libraries that can be used to implement applications using (Fully) Homomorphic Encryption.

- [cuHE](https://github.com/vernamlab/cuHE) - GPU-accelerated HE library for NVIDIA CUDA-Enabled GPUs.
- [cuFHE](https://github.com/vernamlab/cuFHE) - CUDA-accelerated Fully Homomorphic Encryption Library.
- [cuYASHE](https://github.com/cuyashe-library/cuyashe) - Based on leveled fully HE scheme YASHE for GPGPUs.
- [FHEW](https://github.com/lducas/FHEW) - A Fully HE library based on [_FHEW: Bootstrapping Homomorphic Encryption in less than a second_](https://eprint.iacr.org/2014/816).
- [FV-NFLlib](https://github.com/CryptoExperts/FV-NFLlib) - A header-only library implementing the Fan-Vercauteren scheme.
- [HEAAN](https://github.com/snucrypto/HEAAN) -  Scheme with native support for fixed point approximate arithmetic.
- [HElib] - Brakerski-Gentry-Vaikuntanathan (BGV) scheme.
- [krypto](https://github.com/kryptnostic/krypto) - C++ implementation of multivariate quadratic FHE.
- [HLearn](https://github.com/mikeizbicki/HLearn) - Haskell high performance machine learning library written
- [Λ ○ λ](https://github.com/cpeikert/Lol) - "Lol" Haskell library for ring-based lattice cryptography that supports FHE.
- [lattigo](https://github.com/ldsec/lattigo) - Go library for lattice-based crypto that implements various schemes.
- [libScarab](https://github.com/hcrypt-project/libScarab) - C library implementing a FHE scheme using large integers.
- [libshe](https://github.com/bogdan-kulynych/libshe) - Symmetric somewhat HE library based on DGHV scheme.
- [NFLlib](https://github.com/quarkslab/NFLlib) - NTT-based Fast Lattice library specialized on power-of-two polynomials.
- [node-seal](https://github.com/morfix-io/node-seal) - JavaScript/WebAssembly port of [SEAL].
- [NuFHE](https://github.com/nucypher/nufhe) - GPU-accelerated HE library, faster than cuFHE, that implements the [tfhe] algorithms.
- [Microsoft SEAL] - C++ FHE library implementing BFV and CKKS schemes.
- [PALISADE] - lattice encryption library.
- [petlib](https://github.com/gdanezis/petlib) - Python library that implements a number of Privacy Enhancing Technologies.
- [python-paillier](https://github.com/n1analytics/python-paillier) - Partially HE based on Paillier scheme.
- [SEAL] - "FullRNS" optimization of Fan-Vercauteren (FV) scheme.
- [Pyfhel](https://github.com/ibarrond/Pyfhel) - A Python wrapper for [SEAL], [HElib], and [PALISADE].
- [PySEAL](https://github.com/Lab41/PySEAL) - This code wraps the [SEAL] build in a docker container and provides Python API's to the encryption library.
- [SparkFHE](https://github.com/SpiRITlab/spark) - Apache Spark with an add-on for FHE computations. See [:page_facing_up:](https://homomorphicencryption.org/wp-content/uploads/2019/08/poster_5.pdf).
- [tfhe] - Faster fully HE: Bootstrapping in less than 0.1 seconds.
- [nGraph-HE](https://github.com/NervanaSystems/he-transformer) - Deep learning with Homomorphic Encryption (HE) through Intel nGraph.


[SEAL]: http://sealcrypto.org
[HElib]: https://github.com/homenc/HElib
[Microsoft SEAL]: https://github.com/microsoft/SEAL
[PALISADE]: https://git.njit.edu/palisade/PALISADE
[tfhe]: https://github.com/tfhe/tfhe

## Software

- [ALCHEMY](https://github.com/cpeikert/ALCHEMY) - Haskell-based DSLs and interpreters/compilers, build on top of the lattice crypto library Lol.

## Software

- [Cingulata](https://github.com/CEA-LIST/Cingulata) - Compiler toolchain and RTE for running C++ programs over encrypted data.
- [crypto-geofence](https://github.com/Georeactor/crypto-geofence) - Geo-fencing demo application based on Paillier scheme.
- [nGraph-HE](https://github.com/NervanaSystems/he-transformer) - Deep Learning (DL) with HE through Intel’s DL graph compiler nGraph based on [SEAL].
- [Marble](https://github.com/MarbleHE/Marble) - A C++ framework that translates between nearly plaintext-style user programs and FHE computations.
- [Morfix.io](https://morfix.io/sandbox) - Web-based UI to play around with the [Microsoft SEAL] library.
- [OpenMined](https://github.com/OpenMined) - Decentralized data ownership & intelligence based on HE, blockchain and deep / federated learning.
- [SHEEP](https://github.com/alan-turing-institute/SHEEP) - HE evaluation platform with a set of native benchmarks and a library agnostic language.

## Databases

- [CryptDB](https://github.com/CryptDB/cryptdb) - Protecting confidentiality with encrypted query processing.
- [encrypted-mongodb](https://github.com/pdroalves/encrypted-mongodb) - Wrapper on MongoDB's Python driver that enables to query encrypted data.
- [Prisma/DB](https://github.com/PrismaDB/PrismaDB) - Security layer for relational database systems.
- [TimeCrypt](https://github.com/TimeCrypt/timecrypt) - Encrypted time-series database using homomorphic encryption-based access control.
- [ZeroDB](https://github.com/zerodb/zerodb) - E2E encrypted database using proxy re-encryption.

## Resources

- [Barak, Boaz](https://intensecrypto.org/public/lec_15_FHE.html). Chapter about FHE in Barak's introductory book to Cryptography, used for Harvard CS 127.
- [Barthelemy, Lucas](https://blog.quarkslab.com/a-brief-survey-of-fully-homomorphic-encryption-computing-on-encrypted-data.html). Brief survey of Fully HE. 2016.
- [Chen, Zhigang](https://zhigang-chen.github.io/A%20List%20of%20FHE%20Papers.html). A continuously updated list of FHE papers.
- [Gentry, Craig](https://crypto.stanford.edu/craig/craig-thesis.pdf). A fully homomorphic encryption scheme. Stanford University, 2009.
- [HomomorphicEncryption.org](https://homomorphicencryption.org). An open industry, government & academic consortium working on standardization of FHE.
- [KU Leuven](https://www.esat.kuleuven.be/cosic/tag/cosic-guide-to-crypto/). An introduction to homomorphic encryption.
- [Micciancio, Daniele](http://cseweb.ucsd.edu/~daniele/LatticeLinks/FHE.html). Links to papers and implementations of Lattice Cryptography schemes.
- [Microsoft Research](https://www.youtube.com/playlist?list=PLD7HFcN7LXRef-eTSGt_XOUJLZNoDINUn). Videos from SEAL/CKKS talks at Microsoft's Private AI Bootcamp.
- [Vaikuntanathan, Vinoid](https://people.csail.mit.edu/vinodv/FHE/FHE-refs.html). A list of references about FHE, covering top papers in the field.
- [Vinoid Vaikuntanathan](https://people.csail.mit.edu/vinodv/FHE/FHE-refs.html). A list of references about FHE, covering top papers in the field.
- [Zhigang Chen](https://zhigang-chen.github.io/FHE%20and%20Machine%20Learning%20References.html). FHE and Machine Learning References

## Papers

-  FV algorithm
    - https://eprint.iacr.org/2012/144.pdf
- [Daniele Micciancio](http://cseweb.ucsd.edu/~daniele/LatticeLinks/FHE.html). Links to papers and implementations of Lattice Cryptography schemes.
- [HomomorphicEncryption.org](https://homomorphicencryption.org). An open industry, government, and academic consortium for working on standardization of FHE.

## Related awesome lists

- [awesome-cryptography](https://github.com/sobolevn/awesome-cryptography)
- [awesome-crypto-papers](https://github.com/pFarb/awesome-crypto-papers)
- [awesome-mpc](https://github.com/rdragos/awesome-mpc) - Multi-Party Computation.


## Misc

- Implement FV Homomorphic Encryption from Scratch in GSoC
    - https://github.com/OpenMined/PySyft/issues/3097
    
## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Jonathan Schneider has waived all copyright and
related or neighboring rights to this work.
