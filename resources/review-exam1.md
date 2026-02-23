# Exam 1 Topic List (Fall 2026)

## Format

- Open notes: bring as much printed material as you want
- Closed computers / phones / everything else
- Should take only 30-40 minutes
- If you successfully completed the homework assignments, the questions should be easy
- Multiple choice and short answer (no coding or writing proofs)
- Liberal partial credit applied - if unsure, explain your reasoning (even for multiple-choice questions)

## Models of Secure Computation

- Outsourced computation
- Multiparty computation

## Finite Fields

- Definition
- Operations (+, *, multiplicative inverse)
- Why do we need them (randomness)
- Why does the characteristic need to be prime (multiplicative inverse)

## Defining Security

- Trusted third party
- Ideal functionality
- Real/Ideal paradigm
  - Anything you can learn from the protocol, you can also learn from the ideal functionality
- Proof of security by constructing a simulator
  - Constructive proof of the above

## Additive Secret Sharing

- Definition
- Security property
- Additive homomorphism
- No multiplicative homomorphism

## Shamir Secret Sharing

- Definition (including parameters `t` and `n`)
- Security property
- Reconstruction via interpolation
- Additive homomorphism
- (Limited) multiplicative homomorphism

## Specific-Purpose Protocols

- Summation (via secret sharing)
- Multiplication of additive shares (via multiplication triples)
- Generating binary multiplication triples with OT
- Generating arithmetic multiplication triples with OT
- Oblivious transfer (OT)
- GRR multiplication (for Shamir secret sharing)

## Circuit-Based MPC Protocols

- Circuit definitions
  - Binary circuits
  - Arithmetic circuits
- Multiplication triple protocol (binary or arithmetic circuits; 2 or n parties; additive secret sharing + multiplication triples)
- GMW protocol (binary circuits, 2 parties; additive secret sharing + OT)
- Yao's Garbled Circuit protocol (binary circuits, 2 parties; wire labels + garbled tables)
- BGW protocol (arithmetic circuits, `n` parties; Shamir secret sharing + degree reduction)
- Strengths and weaknesses of each
