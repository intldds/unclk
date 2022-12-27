# Session 1 Exercise Solutions

## Chapter 1 - The Context of Cryptography

- **1.10.** Describe a concrete example where improving the security of a system against one type of attack can increase the likelihood of other attacks.

>**Answer:**
>
> While walls can provide a physical barrier against certain types of attacks, they can also create a false sense of security that can make a house more vulnerable to 
other types of attacks. For instance, if a house has walls, the occupants may feel more secure and be less vigilant about locking doors and windows or taking other security measures. This can make the house more vulnerable to attacks that do not require physical force, such as social engineering attacks or attacks that exploit security vulnerabilities in the house's electronic systems. Additionally, walls can provide attackers with cover and concealment, making it easier for them to approach the house undetected and launch other types of attacks.

## Chapter 2 - Introduction to Cryptography

- **Q3.** Consider a group of 30 people who wish to establish pair-wise secure communications using symmetric-key cryptography. How many keys need to be exchanged in total?

>**Answer:**
>
> In this case, the number of keys that need to be exchanged is equal to the number of pairs of people who wish to communicate securely. Since each person will need a separate key for each person they want to communicate with, the total number of keys that need to be exchanged is equal to the number of pairs of people in the group. 
> To calculate the number of pairs in a group of 30 people, we can use the formula for the number of pairs in a group of n elements:
number of pairs = n(n-1)/2
> 
> Plugging in n=30, we get:
>number of pairs = 30(29)/2 = 435
> 
>So, in total, 435 keys will need to be exchanged in order to establish pair-wise secure communications between the 30 people in the group.


- **Q4.** Suppose Bob receives a messages signed using a digital signature scheme with Alice's secret signing key. Does it prove that Alice saw the message and chose to sign.

>**Answer:**
>
> No, some malicious actor may have got access to Alice's computer and forge her signature.


- **Q6.** Suppose a chosen-ciphertext attacker cannot recover the secret decryption key for an encryption scheme. Does this mean the encryption scheme is secure?

>**Answer:**
>
> No, the attacker may still recover information about the message (broken diffusion), even if they cannot recover information about the key (successful confusion).


- **Q7.** Consider a symmetric-key cryptosystem in which cryptographic keys are randomly selected from the set of all n-bit strings. Approximately what should n be in order to provide 128 bits of security against a birthday attack?

>**Answer:**
>
> To calculate the minimum length of the keys needed to provide this level of security, we can use the formula:
>
> n = -log2(1/p)
>
> Where n is the length of the keys in bits and p is the probability of finding two keys with the same value.
>
> Plugging in p=2^(-128), we get:
>
> n = -log2(1/(2^(-128))) = 128



