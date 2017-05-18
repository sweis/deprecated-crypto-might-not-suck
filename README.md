Crypto Projects that Might not Suck
===================================

This document originated with an informal survey of Twitter and several mailing lists asking for nominations for crypto projects that "didn't suck". Over 100 nominations were received and culled down to this list. Projects marked with an "☢" symbol are relatively new and considered experimental. Apologies to project creators who are omitted. Corrections are welcome via pull request.


End User Tool Summary
---------------------
This is a quick summary of tools that are generally recommended for end users. See the [EFF's Surveillance Self Defense guides](https://ssd.eff.org/en) or  [Press Freedom Foundation's Encryption Works](https://freedom.press/encryption-works) guide for more information.

* [GPG](https://www.gnupg.org/): Email encryption. 
   * [EFF PGP Intro](https://ssd.eff.org/en/module/introduction-public-key-cryptography-and-pgp)
   * [Windows PGP Installation](https://ssd.eff.org/en/module/how-use-pgp-windows)
   * [Mac PGP Installation](https://ssd.eff.org/en/module/how-use-pgp-mac-os-x)
   * [Linux PGP Installation](https://ssd.eff.org/en/module/how-use-pgp-linux)
   * [RiseUp: OpenPGP Best Practices](https://riseup.net/en/gpg-best-practices)
* [Signal](https://whispersystems.org/): Encrypted messaging & voice calls
   * [Signal Source](https://github.com/WhisperSystems?utf8=%E2%9C%93&query=Signal)
   * EFF Signal Guide for [Android](https://ssd.eff.org/en/module/how-use-signal-android) or [iOS](https://ssd.eff.org/en/module/how-use-signal-ios) 
* [Tor](https://www.torproject.org/): Protect from network surveillance 
   * [Windows Tor Installation](https://ssd.eff.org/en/module/how-use-tor-windows)
   * [Mac OS X Tor Installation](https://ssd.eff.org/en/module/how-use-tor-mac-os-x)

The People’s Choice
-------------------
* Open Whisper Systems: https://whispersystems.org/
    * Moxie Marlinspike (@moxie) & open source community
* Signal: Encrypted messaging & phone calls for iPhone and Android
    * Calls: ZRTP for key agreement, SRTP for call encryption
    * Messaging: OTR-like forward security & Axolotl key ratcheting by @trevp__
    * https://github.com/WhisperSystems?utf8=%E2%9C%93&query=Signal

Honorable Mentions
-----------------
* Networking and Crypto Library (NaCl): http://nacl.cr.yp.to/
    * Easy to use, high speed XSalsa20, Poly1305, Curve25519, etc
    * No dynamic memory allocation or data-dependent branches
    * DJ Bernstein (@hashbreaker), Tanja Lange (@hyperelliptic), Peter Schwabe (@cryptojedi)
* libsodium: https://github.com/jedisct1/libsodium
    * Portable, cross-compatible NaCL
    * OpenDNS & Frank Denis (@jedisct1)
* Tor: https://www.torproject.org/

The SSL Libraries
-----------------
* OpenSSL: Seriously. https://www.openssl.org/
* ☢ LibreSSL: http://www.libressl.org/
    * Hilarious code reviews
    * OpenBSD team and Bob Beck (@bob_beck)
* BoringSSL: https://boringssl.googlesource.com/boringssl/
    * Google’s OpenSSL fork by Adam Langley (@agl__)

JavaScript Crypto Libraries
---------------------------
* Stanford JS Crypto Lib (SJCL): https://crypto.stanford.edu/sjcl/
    * Emily Stark, Mike Hamburg, & Dan Boneh
    * Used in several products, e.g. Crypton.io
* ☢ Microsoft JS Crypto Library
    * 800 MB of test vectors for 9000 lines of code
    * Non-commercial and research license only
* libsodium.js: https://github.com/jedisct1/libsodium.js
    * libsodium crypto library compiled to pure JavaScript using Emscripten.
    * Automatically generated wrappers to make it easy to use in web applications.

Online Storage
--------------
* Tahoe-LAFS: https://tahoe-lafs.org/
    * Distributed, provider-independent cloud storage
    * Least Authority Systems, Zooko (@zooko), et al.
* Tarsnap: http://www.tarsnap.com/
    * Client-side encryption; must build from source
    * Commercial service archives on S3
    * Colin Percival (@cperciva)

Libraries and Frameworks
------------------------

* Crypto++: http://www.cryptopp.com/
    * Long-lived C++ crypto library by Wei Dai
* go.crypto: https://golang.org/pkg/crypto/
* Noise Framework: http://noiseprotocol.org/
    * Framework for building crypto protocols
* ☢ Cryptography.io: https://cryptography.io/
    * Attempt to build a good Python crypto library
    * Paul Kehrer (@reaperhulk) & Alex Gaynor (@alex_gaynor)
* ☢ ECClib: https://www.microsoft.com/en-us/research/project/msr-elliptic-curve-cryptography-library/
    * Microsoft Research & Patrick Longa (@PatrickLonga)
* libtomcrypt: https://github.com/libtom/libtomcrypt
    * A fairly comprehensive, modular and portable cryptographic toolkit

Post Quantum Libraries
-----------------
* ☢ New Hope: https://github.com/Yawning/newhope
  * Post-quantum key exchange by Peter Schwabe (@cryptojedi) et al.
  * Paper: https://cryptojedi.org/papers/newhope-20160328.pdf
* ☢☢ Microsoft Supersingular Isogeny Diffie Hellman Library (SIDH): https://www.microsoft.com/en-us/research/project/sidh-library/

Community Efforts
-----------------
* Open Crypto Audit Project (OCAP): https://opencryptoaudit.org/
    * Audited TrueCrypt. Great technical advisory board.
* Better Crypto: https://bettercrypto.org/
    * Community-generated guidelines for applied crypto hardening
* Crypto Coding Standard: https://cryptocoding.net/
* ☢ Password Hashing Competition: https://password-hashing.net/
    * Community-driven contest for password hashing replacement
* ☢ Safe Curves: http://safecurves.cr.yp.to/
    * Criteria to ensure elliptic-curve crypto security
    * DJ Bernstein (@hashbreaker) & Tanja Lange (@hyperelliptic)

Experimental Toolkits
---------------------
* ☢ Advanced Crypto Software Collection: http://hms.isi.jhu.edu/acsc/
* ☢ Relic Toolkit: https://github.com/relic-toolkit/relic
    * Bilinear maps, pairing-based crypto, ID-based crypto
    * Implemented in C
    * Diego Aranha (@dfaranha) and C.P. L. Gouvêa
* ☢ CHARM: http://www.charm-crypto.com/
    * Tool for rapid cryptographic prototyping
    * Bilinear maps, multiparty protocol engine, non-interactive ZK
    * Python with native C modules
    * JHU ISI: J. Ayo Akinyele (@ja_akinyele), et al.

Certificate and Key Management Tools
------------------------------------
* Let's Encrypt: Open source certificate authority & free service
    * Available as a service: https://letsencrypt.org/
    * Go source code: https://github.com/certbot/certbot
* ☢ CFSSL: https://github.com/cloudflare/cfssl 
    * Command line tool and an HTTP API server for signing, verifying, and bundling TLS certificates
    * Implemented in Go
* ☢ Red October: https://github.com/cloudflare/redoctober
    * Encryption and decryption server enforcing a two-person rule
    * Implemented in Go
* ☢ KeyWhiz: https://github.com/square/keywhiz
    * A system for distributing and managing secrets
    * Implemented in Java
* ☢ Vault: https://github.com/hashicorp/vault
    * A tool for managing secrets
    * Implemented in Go

Verification & Automation Tools
-------------------------------
* Cryptol: http://cryptol.net/
    * Domain-specific language for specifying crypto algorithms
    * Galois Inc. & Adam C. Foltzer (@acfoltzer)
    * Works with Software Analaysis Workbench (SAW): https://galois.com/project/software-analysis-workbench/
* ☢ AutoTools: https://github.com/JHUISI/auto-tools
    * Python tools for transforming cryptographic primitives in different and interesting ways
    * JHU ISI: J. Ayo Akinyele (@ja_akinyele), et al.
* ☢ EasyCrypto: https://www.easycrypt.info/trac/
    * Computer-Aided Cryptographic Proofs
* ☢ CertiCrypt: http://certicrypt.gforge.inria.fr/
    * Computer-Aided Cryptographic Proofs in Coq
* ☢ Tamarin Security Protocol Verification: https://github.com/tamarin-prover/tamarin-prover
* ☢ gfverif: http://gfverif.cryptojedi.org/
    * Fast and easy verification of finite-field arithmetic
  
Miscellaneous Project
---------------------
* ☢ spiped: http://www.tarsnap.com/spiped.html
    * Secure pipe daemon
    * Similar to ‘ssh -L’ but requires pre-established secret
    * Colin Percival (@cperciva)
* ☢ libsnark: https://github.com/scipr-lab/libsnark
    * C++ library for zero-knowledge proof system with succinct proofs
    * Eli Ben-Sasson, Alessandro Chiesa, Eran Tromer, and Madars Virza
* ☢ libmacaroons: https://github.com/rescrv/libmacaroons
    * Decentralized authentication for distributed systems
    * Paper: Chalmers/Brown/Google; Code: Robert Escriva (@rescrv)
* ☢ magic-wormhole: https://github.com/warner/magic-wormhole
    * "Get things from one computer to another, safely."
    * Built on NaCL
    * Brian Warner (@lotharrr)
* ☢ Wireguard: https://www.wireguard.io
    * Modern VPN tunnel
    * Built on Noise, Curve25519, etc.
    * Jason Donenfeld (@zx2c4)

Learning and Resources
-----------------
* Matasano Crypto Challenges (@tqbf): http://cryptopals.com/
* Thomas Ptacek's Cryptographic "Right Answers": https://gist.github.com/tqbf/be58d2d39690c3b366ad
* Underhanded Crypto Contest: https://underhandedcrypto.com
* Modern Crypto mailing lists (@trevp__): https://moderncrypto.org/
* CryptoBib bibliography (@daeinar): https://cryptobib.di.ens.fr/ (Source: https://github.com/cryptobib)
* 52 Things People Should Know To Do Cryptography: http://www.cs.bris.ac.uk/Research/CryptographySecurity/knowledge.html
* Crypto101 Introductory course: https://www.crypto101.io/
* Dan Boneh's Coursera Cryptography course: https://www.coursera.org/course/crypto
* Dan Boneh's Coursera Cryptography II course: Coming in 2024.
* Dan Boneh & Victor Shoup's "A Graduate Course in Applied Cryptography": https://crypto.stanford.edu/~dabo/cryptobook/draft_0_3.pdf
* Lars R. Knudsen & Matthew J.B. Robshaw's "The Block Cipher Companion": http://antoanthongtin.vn/Portals/0/UploadImages/kiennt2/Sach/Sach-CSDL4/The_Block_Cipher_Companion.pdf

Maybe Sucky Secret Managers
-----------------
There are many secret key value managers and I don't know which are any good. Including them here for future reference:
* ☢ KeyWhiz: https://github.com/square/keywhiz
* ☢ Vault: https://github.com/hashicorp/vault
* ☢ Knox: https://github.com/pinterest/knox 
* ☢ Confidant: https://github.com/lyft/confidant 
* ☢ Secretary: https://github.com/meltwater/secretary
* ☢ Sops: https://github.com/mozilla/sops
* ☢ Summon: https://github.com/conjurinc/summon
* ☢ Biscuit: https://github.com/dcoker/biscuit 
