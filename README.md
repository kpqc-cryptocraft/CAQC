# CAQC

## Overview

**CAQC** is an open-source project that provides quantum circuit implementations for a variety of cryptographic algorithms, including AES, SHA-2, SHA-3, and binary ECC.  
This project benchmarks the quantum resources required to attack these cryptosystems using Grover’s and Shor’s algorithms (resp. for symmetric key and asymmetric key cryptography).
The goal is to provide reproducible resource estimation results for the quantum cryptanalysis and post-quantum security research community.

## Features

- Quantum circuit implementations for:
  - AES (Advanced Encryption Standard) family  (e.g., AES-128)
  - SHA-2 family (e.g., SHA-256)
  - SHA-3 family (e.g., SHA3-256)
  - Binary Elliptic Curve Cryptography (ECC) for Shor’s ECDLP attack

- Resource estimation scripts for:
  - Qubit count, gate count, circuit depth, T-count, T-depth
  - Benchmarking attack costs under Grover’s algorithm (for symmetric ciphers and hash functions) and Shor’s algorithm (for ECC)

