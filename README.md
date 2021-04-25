# Awesome Homomorphic Encryption [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)


> A curated list of amazing Homomorphic Encryption libraries, software and resources.


## Contents

- [Libraries](#libraries)
- [Toolkits](#toolkits)
- [Applications](#applications)
- [Databases](#databases)
- [Resources](#resources)
- [Papers](#Papers)

## Libraries

Libraries that can be used to implement applications using (Fully) Homomorphic Encryption.
- [concrete](https://github.com/zama-ai/concrete) - Rust FHE library that implements Zama's variant of TFHE.
- [cuHE](https://github.com/vernamlab/cuHE) - GPU-accelerated HE library for NVIDIA CUDA-Enabled GPUs.
- [cuFHE](https://github.com/vernamlab/cuFHE) - CUDA-accelerated Fully Homomorphic Encryption Library.
- [cuYASHE](https://github.com/cuyashe-library/cuyashe) - Based on leveled fully HE scheme YASHE for GPGPUs.
- [FHEW](https://github.com/lducas/FHEW) - A Fully HE library based on [_FHEW: Bootstrapping Homomorphic Encryption in less than a second_](https://eprint.iacr.org/2014/816).
- [FV-NFLlib](https://github.com/CryptoExperts/FV-NFLlib) - A header-only library implementing the Fan-Vercauteren scheme.
- [HEAAN](https://github.com/snucrypto/HEAAN) -  Scheme with native support for fixed point approximate arithmetic.
- [HElib] - Brakerski-Gentry-Vaikuntanathan (BGV) scheme.
- [HEAAN-Python](https://github.com/Huelse/HEAAN-Python) - Python binding for the [HEANN](#HEAAN) library.
- [krypto](https://github.com/kryptnostic/krypto) - C++ implementation of multivariate quadratic FHE.
- [HLearn](https://github.com/mikeizbicki/HLearn) - Haskell high performance machine learning library written
- [IBM FHE Toolkit for MacOS](https://github.com/IBM/fhe-toolkit-macos) - XCode packaged HElib for MacOS
- [IBM FHE Toolkit for iOS](https://github.com/IBM/fhe-toolkit-ios) - XCode packaged HElib for iOS
- [Integer Vector Homomorphic Encryption](https://github.com/jamespayor/vector-homomorphic-encryption) - MIT 6.857 project - HE scheme permitting addition, linear transformation, and weighted inner products of integer vectors, whilst encrypted.
- [Λ ○ λ](https://github.com/cpeikert/Lol) - "Lol" Haskell library for ring-based lattice cryptography that supports FHE.
- [Lattigo](https://github.com/ldsec/lattigo) - Go library for lattice-based crypto that implements various schemes.
- [libScarab](https://github.com/hcrypt-project/libScarab) - C library implementing a FHE scheme using large integers.
- [libshe](https://github.com/bogdan-kulynych/libshe) - Symmetric somewhat HE library based on DGHV scheme.
- [Microsoft SEAL](https://github.com/microsoft/SEAL) - C++ FHE library implementing BFV and CKKS schemes.</a>
- [NFLlib](https://github.com/quarkslab/NFLlib) - NTT-based Fast Lattice library specialized on power-of-two polynomials.
- [node-seal](https://github.com/morfix-io/node-seal) - JavaScript/WebAssembly port of [SEAL].
- [NuFHE](https://github.com/nucypher/nufhe) - GPU-accelerated HE library, faster than cuFHE, that implements the [tfhe] algorithms.
- [Microsoft SEAL] - C++ FHE library implementing BFV and [CKKS] schemes.
- [PALISADE] - lattice encryption library.
- [Paillier](https://github.com/mikeivanov/paillier) - Very basic pure Python implementation of the Paillier Homomorphic Cryptosystem
- [petlib](https://github.com/gdanezis/petlib) - Python library that implements a number of Privacy Enhancing Technologies.
- [python-paillier](https://github.com/data61/python-paillier) - Partially HE based on Paillier scheme.
- [SEAL] - "FullRNS" optimization of Fan-Vercauteren (FV) scheme.
- [Pyfhel](https://github.com/ibarrond/Pyfhel) - A Python wrapper for [SEAL], [HElib], and [PALISADE].
- [PySEAL](https://github.com/Lab41/PySEAL) - This code wraps the [SEAL] build in a docker container and provides Python API's to the encryption library.
- [she-wasm](https://github.com/herumi/she-wasm) - Two-level homomorphic encryption for Node.js by WebAssembly
- [SparkFHE](https://github.com/SpiRITlab/spark) - Apache Spark with an add-on for FHE computations. See [:page_facing_up:](https://homomorphicencryption.org/wp-content/uploads/2019/08/poster_5.pdf).
- [tfhe] - Faster fully HE: Bootstrapping in less than 0.1 seconds.
- [nGraph-HE](https://github.com/NervanaSystems/he-transformer) - Deep learning with Homomorphic Encryption (HE) through Intel nGraph.

=======
- [node-seal](https://github.com/morfix-io/node-seal) - JavaScript/WebAssembly port of [Microsoft SEAL](#SEAL).
- [NuFHE](https://github.com/nucypher/nufhe) - GPU-accelerated HE library, faster than cuFHE, that implements the [tfhe](#tfhe) algorithms.
- <a name="PALISADE">[PALISADE](https://palisade-crypto.org/software-library) - lattice encryption library.
- [petlib](https://github.com/gdanezis/petlib) - Python library that implements a number of Privacy Enhancing Technologies.
- [Pyfhel](https://github.com/ibarrond/Pyfhel) - A Python wrapper for [SEAL](#SEAL), [HElib](#HElib), and [PALISADE](#PALISADE).
- [python-paillier](https://github.com/data61/python-paillier) - Partially HE based on Paillier scheme.
- [SEAL-python](https://github.com/Huelse/SEAL-Python/) - Python binding for the [Microsoft SEAL](#SEAL) library.
- [SparkFHE](https://github.com/SpiRITlab/spark) - Apache Spark with an add-on for FHE computations. See [:page_facing_up:](https://homomorphicencryption.org/wp-content/uploads/2019/08/poster_5.pdf).
- <a name="tfhe">[tfhe](https://github.com/tfhe/tfhe) - Faster fully HE: Bootstrapping in less than 0.1 seconds.</a>
- [TenSEAL](https://github.com/OpenMined/TenSEAL) - Library for HE operations on tensors, built on [Microsoft SEAL](#SEAL), with a Python API.
>>>>>>> 4fe4efdd197d253b0f19a5e2688e74a9f49d2bdc

[SEAL]: http://sealcrypto.org
[HElib]: https://github.com/homenc/HElib
[Microsoft SEAL]: https://github.com/microsoft/SEAL
[PALISADE]: https://git.njit.edu/palisade/PALISADE
[tfhe]: https://github.com/tfhe/tfhe

## Toolkits

- [ALCHEMY](https://github.com/cpeikert/ALCHEMY) - Haskell-based DSLs and interpreters/compilers, build on top of the lattice crypto library Lol.
- [AWS HE toolkit](https://github.com/awslabs/homomorphic-implementors-toolkit) - Simplifies the process of designing circuits for the CKKS scheme.
- [Cingulata](https://github.com/CEA-LIST/Cingulata) - Compiler toolchain and RTE for running C++ programs over encrypted data.
- [E3](https://github.com/momalab/e3) - Encrypt-Everything-Everywhere framework for compiling C++ programs with encrypted operands.
- [IBM FHE toolkit](https://fhe-website.mybluemix.net) - Including FHE ML inference with a Neural Network and a Privacy-Preserving key-value search.
	- [fhe-toolkit-android](https://github.com/IBM/fhe-toolkit-android) - IBM FHE toolkit for Android
	- [fhe-toolkit-ios](https://github.com/IBM/fhe-toolkit-ios) - IBM FHE toolkit for iOS
	- [fhe-toolkit-linux](https://github.com/IBM/fhe-toolkit-linux) - IBM FHE toolkit for Linux (Docker based Centos, Fedora, Ubuntu & Alpine editions) 
	- [fhe-toolkit-macos](https://github.com/IBM/fhe-toolkit-macos) - IBM FHE toolkit for macOS
- [Marble](https://github.com/MarbleHE/Marble) - C++ framework that translates between nearly plaintext-style user programs and FHE computations.
- [SHEEP](https://github.com/alan-turing-institute/SHEEP) - HE evaluation platform with a set of native benchmarks and a library agnostic language.


## Applications

- [crypto-geofence](https://github.com/Georeactor/crypto-geofence) - Geo-fencing demo application based on Paillier scheme.
- [nGraph-HE](https://github.com/NervanaSystems/he-transformer) - Deep Learning (DL) with HE through Intel’s DL graph compiler nGraph based on [SEAL].
- [Marble](https://github.com/MarbleHE/Marble) - A C++ framework that translates between nearly plaintext-style user programs and FHE computations.
- [Morfix.io](https://morfix.io/sandbox) - Web-based UI to play around with the [Microsoft SEAL] library.
- [lattigo-polls](https://github.com/ldsec/lattigo-polls-demo) - Web-application for scheduling meetings using [lattigo](#lattigo).
- [Morfix.io](https://morfix.io/sandbox) - Web-based UI to play around with the [Microsoft SEAL](#SEAL) library.
- [nGraph-HE](https://github.com/IntelAI/he-transformer) - Deep Learning (DL) with HE through Intel’s DL graph compiler nGraph based on [SEAL](#SEAL).
- [OpenMined](https://github.com/OpenMined) - Decentralized data ownership & intelligence based on HE, blockchain and deep / federated learning.
- [Rosetta](https://github.com/LatticeX-Foundation/Rosetta) - A privacy-preserving framework based on TensorFlow.
- [tf-encrypted](https://github.com/tf-encrypted/tf-encrypted) - Bridge between TensorFlow and the [Microsoft SEAL](#SEAL) library. 


## Databases

- [CryptDB](https://github.com/CryptDB/cryptdb) - Protecting confidentiality with encrypted query processing.
- [encrypted-mongodb](https://github.com/pdroalves/encrypted-mongodb) - Wrapper on MongoDB's Python driver that enables to query encrypted data.
- [Prisma/DB](https://github.com/PrismaDB/PrismaDB) - Security layer for relational database systems.
- [TimeCrypt](https://github.com/TimeCrypt/timecrypt) - Encrypted time-series database using homomorphic encryption-based access control.
- [ZeroDB](https://github.com/zerodb/zerodb) - E2E encrypted database using proxy re-encryption.

## Resources

- [Fully Homomorphic Encryption from the Ground Up](https://www.youtube.com/watch?v=TySXpV86958). Talk at Eurocrypt 2019 by Daniele Micciancio, UC San Diego.
- [Barak, Boaz](https://intensecrypto.org/public/lec_15_FHE.html). Chapter about FHE in Barak's introductory book to Cryptography, used for Harvard CS 127.
- [Barthelemy, Lucas](https://blog.quarkslab.com/a-brief-survey-of-fully-homomorphic-encryption-computing-on-encrypted-data.html). Brief survey of Fully HE. 2016.
- [Chatterjee, Sengupta](https://eprint.iacr.org/2015/981.pdf) - Searching and Sorting of Fully Homomorphic
Encrypted Data on Cloud
- [Chen, Zhigang](https://zhigang-chen.github.io/A%20List%20of%20FHE%20Papers.html). A continuously updated list of FHE papers.
- [Gentry, Craig](https://crypto.stanford.edu/craig/craig-thesis.pdf). A fully homomorphic encryption scheme. Stanford University, 2009.
- [HomomorphicEncryption.org](https://homomorphicencryption.org). An open industry, government & academic consortium working on standardization of FHE.
- [KU Leuven](https://www.esat.kuleuven.be/cosic/tag/cosic-guide-to-crypto/). An introduction to homomorphic encryption.
- [Lepoint, Naehrig](https://eprint.iacr.org/2014/062) - A Comparison of the Homomorphic Encryption Schemes FV and YASHE
- [Micciancio, Daniele](http://cseweb.ucsd.edu/~daniele/LatticeLinks/FHE.html). Links to papers and implementations of Lattice Cryptography schemes.
- [Microsoft Research](https://www.youtube.com/playlist?list=PLD7HFcN7LXRef-eTSGt_XOUJLZNoDINUn). Videos from [SEAL]/[CKKS] talks at Microsoft's Private AI Bootcamp.
- [Sun, X. Q.](https://doi.org/10.1007%2Fs10773-017-3275-0) - An efficient quantum somewhat homomorphic symmetric searchable encryption. 
- [Vaikuntanathan, Vinoid](https://people.csail.mit.edu/vinodv/FHE/FHE-refs.html). A list of references about FHE, covering top papers in the field.
- [Vinoid Vaikuntanathan](https://people.csail.mit.edu/vinodv/FHE/FHE-refs.html). A list of references about FHE, covering top papers in the field.
- [Yu, Lai, Payor](https://courses.csail.mit.edu/6.857/2015/files/yu-lai-payor.pdf). Writup of the scheme behind Integer Vector Homomorphic Encryption.
- [Zhigang Chen](https://zhigang-chen.github.io/FHE%20and%20Machine%20Learning%20References.html). FHE and Machine Learning References
- [Zhou, Wornell](https://pdfs.semanticscholar.org/c386/37e3e2a12eff8c42d82a78e6352da80818a2.pdf)
- [Zhou, Lu, Sun, Li](https://www.nature.com/articles/s41598-020-61791-9) Quantum Search on Encrypted Data Based on Quantum Homomorphic Encryption

## Videos

- [The CKKS (a.k.a. HEAAN) FHE Scheme](https://simons.berkeley.edu/talks/heaan-fhe) - Video on CKKS

## Papers

- Brakerski/Fan-Vercauteren ([FV]/BFV) algorithm
- Cheon, Kim, Kim and Song ([CKKS]/[CKKS17]) (aka HEEAN - Homomorphic Encryption for Arithmetic of Approximate Numbers) algorithm

- [Daniele Micciancio](http://cseweb.ucsd.edu/~daniele/LatticeLinks/FHE.html). Links to papers and implementations of Lattice Cryptography schemes.
- [HomomorphicEncryption.org](https://homomorphicencryption.org). An open industry, government, and academic consortium for working on standardization of FHE.

[FV]: https://eprint.iacr.org/2012/144.pdf
[CKKS17]: https://eprint.iacr.org/2012/144.pdf
[CKKS]: https://eprint.iacr.org/2018/931.pdf
- [Zhigang Chen](https://zhigang-chen.github.io/FHE%20Resources.html). A list of English and Chinese FHE and Machine Learning references.

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
