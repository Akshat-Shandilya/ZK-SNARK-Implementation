# zk-SNARK Implementation in Python

This repository provides an implementation of Zero-Knowledge Succinct Non-Interactive Arguments of Knowledge (zk-SNARKs), designed to offer an insight into the inner workings of zk-SNARKs, their mathematical foundations, and basic cryptographic structures. We have taken references from 

## Overview

zk-SNARKs allow one party (the prover) to demonstrate knowledge of a specific piece of information without revealing it, ensuring both privacy and proof of knowledge in a succinct and efficient way. This implementation explores foundational components like modular arithmetic, elliptic curve cryptography, Rank-1 Constraint Systems (R1CS), and Quadratic Arithmetic Programs (QAPs) to build a basic zk-SNARK framework.

### Key Components

- **Finite Field Arithmetic**: Using the `galois` library to handle modular arithmetic operations over finite fields.
- **Elliptic Curves**: Implemented via `py_ecc` to enable cryptographic operations on elliptic curves.
- **Modular Arithmetic**: Leveraging `libnum` for modular operations essential in zk-SNARKs.
- **Constraint Systems**: Introduction to R1CS, allowing logical statements to be represented as polynomial constraints.
- **Quadratic Arithmetic Programs (QAPs)**: Used to transform R1CS into QAPs, which are crucial for zk-SNARK construction.

