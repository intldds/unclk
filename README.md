# Uncloak

Study group exercises for the Uncloak study group (Nov - March), with Thor and Chloe. On this 
README file I'll just write a short description of the **main topics** discussed in each session/week.


## Session 1 (Nov 18)

- Throughout the learning sessions, we'll cover the book "Cryptography Engineering" by Ferguson, Schneier and
Kohno;
- "Paranoia as a practical skill";
- Cryptography has grown a lot over the last 20 years. Even though it started out as the 
art and science of encryption, nowadays it is much broader, covering  concepts such as authentication, digital signatures, 
zero knowledge proving systems, FHE, MPC, iO and others;
- Chapters 1 and 2 provide an introduction to the field ("high-level overview").


## Session 2 (Nov 25)

- Covering Chapter 2 (introduction)


## Session 3 (Dec 2)

- Covering Chapters 3 and 4 on Block Ciphers and Block Cipher Modes


## Session 4 (Dec 9)

- Covering Chapters 5 and 6 on **Hash Functions** and MACs


## Session 5 (Dec 16)

- Covering Chapter 8 on **implementation issues**

- Rust's compiler enforces, by default, correctness in many ways. NSA urges orgs to use memory-safe programming languages.

- Continuous Integration (CI) should deny changes to your codebase that fail tests, linting, and typically formatting as well.


## Session 6 (Jan 6)

Techniques to obtain compile-time guarantees with Rust. Still chapter 8 about implementation issues.


# Session 7 (Jan 13)

Chapter 9: **randomness**
- How entropy is generated and used to seed a block-cipher based CSPRNG should be the central focus of this chapter.

Chapter 10: **primes**
- The Extended Euclidean Algorithm and the Miller Rabin Primality test are of central focus in this chapter.
- Number Theory is very important


# Session 8 (Jan 20)

Read Chapters 11 and 12 on **Diffie-Hellman** (DH) and **RSA**.

Chapter 11 presents an introduction to the DH protocol in the context of a multiplicative group.
Groups, DH, Man in the Middle attacks, and safe primes are fundamental objects in asymmetric cryptography.

Chapter 12 introduces several results, before presenting RSA encryption. Introduction to The **Chinese Remainder Theorem** (CRT).


## Session 9 (Jan 27)

Chapters 13, 14 and 16

Most of chapter 13 may be skipped, though 13.5.6 on replay attacks is worth covering.
Chapter 14 on key negotiation explores a protocol to obtain a secret session key from an existing secret shared key, for forward secrecy. It's worth a light read of chapter 16.

# Session 10 (Feb 3)

For sessions 10-13, we will be switching gears and covering several sections from "An introduction to mathematical cryptography" 
(henceforth, **ItMC**).

This week's coverage is a partial review of chapters 12 and 13 of "Cryptography Engineering".

**On definitions:**
If you are inexperienced at reading mathematical texts, *some advice*. Of greatest importance are definitions. 
A thorough student will copy each definition into their notes. All the theorems and results follow directly from the 
definitions! Much of the difficulty mathematical development is simply obtaining the correct definitions.

Second, try to understand the crux of each algorithm, theorem, lemma, and proposition, and summarizing in a sentence for your reference.
Example: "Every positive integer has a unique prime factorization", is much easier to remember!

Finally, try to understand the proofs, but don't fret if they don't come naturally to you. Proofs often reveal not 
only the reasoning behind the theorem, but even motivation to further theorems and corollaries. However, proofs are 
often the "hardest" part of reading a mathematical text; only spend as much time as is necessary learning 
proofs: you decide what necessary means.

**Topics of chapter 1 of ItMC**
- basic facts of divisibility, GCD, the Division Algorithm, the Euclidean Algorithm;
- Extended Euclidean Algorithm (EEA), which guarantees that we can easily obtain modular inverses;
- modular arithmetic: Euler's totient function and the Fast Powering Algorithm;
- revisit the Extended Euclidean Algorithm if it is unclear;
- Primitive Root Theorem;
- premise of (binary) encoding schemes.


# Session 11 (Feb 10)

The reading for this week is An Introduction to Mathematical Cryptography Chapter 2.1-2.4, 2.6, 2.7 
A mathematical review of Discrete Log. 
This chapter provides background on the ubiquitous discrete log problem.


# Session 12 (Feb 17)

The reading for this week is An Introduction to Mathematical Cryptography Chapter 4.3 on Probability Theory, 
and 7.1-3 on digital signatures.

The main two signature techniques in practice are those of Schnorr (aka EdDSA, used for instance), and ECDSA, 
with the industry largely moving away from RSA. We will not discuss BLS signatures in this lecture, but we may return to them in week 15.


# Session 13 (Feb 24)

**Elliptic curves**