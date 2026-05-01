# Formal Verification of the Stribog Hash Function (GOST R 34.11-2012)

This repository contains the formal verification of the **Stribog** cryptographic hash function implementation. The project was carried out in collaboration with the **Astra Group** and researchers from the **Ershov Institute of Informatics Systems (IIS)** and **Novosibirsk State University**.

## Project Overview
The primary goal is to ensure the highest level of trust in the implementation of the Russian national hash standard, **GOST R 34.11-2012**. We used formal methods to mathematically prove the correctness of the code, effectively eliminating categories of errors that traditional testing might miss.

## Publication
The methodology and results of this work are published in the following paper:

* **Formal Verification of the Stribog Hash Function Implementation with Astra Group**
* *Published in:* System Informatics (Системная информатика), No. 28 (2025)
* *Authors:* D.A. Kondratyev, L.K. Boyandin, G.E. Gonchar, V.V. Marchenko, A.A. Obukhova, Y.Y. Razbitnova, A.S. Khovanskaya, D.R. Yanbulatov.

## Technical Details
- **Proof Assistant:** [Coq](https://coq.inria.fr/)
- **Scope:** Verification of the compression function, S-box transformations, and linear layers.
- **Goal:** Proving functional correctness and memory safety of the implementation.

## My Contribution
As a member of the research team at Novosibirsk State University, I participated in:
- Formalizing specific mathematical components of the GOST R 34.11-2012 standard.
- Assisting in the development and maintenance of proofs within the Coq environment.
- Contributing to the technical discussions and the preparation of the research paper.

---
*This project was supported by the Mathematical Center in Akademgorodok (Agreement No. 075-15-2025-349).*
