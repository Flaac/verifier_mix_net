# verifier_mix_net
Soon be released

## Project

This project is about implementing a stand alone verifier for the Verificatum Mix-Net. This mix-net is El Gamal-based and uses the Fiat-Shamir heuristic to produce a proof that the software of this project will be able to verify. 

More information about the mix-net can be found : http://verificatum.com/index_splash.html

This implementation is based on one document : http://verificatum.com/files/vmnv-3.0.2.pdf

## Implementation

This implementation is in C++ using GMP (for handling huge numbers), RapidXML (to parse XML) and OpenSSL for a more advanced and secure implementation of the SHA-2 algorithms than mine (cf krypto16).

## Contact
