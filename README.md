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


## Session 7 (Jan 13)

Chapter 9: **randomness**
- How entropy is generated and used to seed a block-cipher based CSPRNG should be the central focus of this chapter.

Chapter 10: **primes**
- The Extended Euclidean Algorithm and the Miller Rabin Primality test are of central focus in this chapter.
- Number Theory is very important


## Session 8 (Jan 20)

Read Chapters 11 and 12 on **Diffie-Hellman** (DH) and **RSA**.

Chapter 11 presents an introduction to the DH protocol in the context of a multiplicative group.
Groups, DH, Man in the Middle attacks, and safe primes are fundamental objects in asymmetric cryptography.

Chapter 12 introduces several results, before presenting RSA encryption. Introduction to The Chinese Remainder Theorem (CRT).


## Session 9 (Jan 27)