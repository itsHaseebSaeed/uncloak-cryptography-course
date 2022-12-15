# Exercises

## From the book

### Ch 1. Q10

> Describe a concrete example where improving the security of a system against one type of attack can increase the likelihood of other attacks.

### FaceID

Now that FaceID has improved significantly, but at the time of launch many new attacks were introduced such as a family member of the owner can easy unlock the phone becase the faical features were almost the same.

### Ch 2. Q3

> Consider a group of 30 people who wish to establish pair-wise secure communications using symmetric-key cryptography. How many keys need to be exchanged in total.

Using the formula n(n-1)2 to calculate the number of keys:
n(n-1)2 where n = 30. So 30(30-1)*2 , 15*29
So 435.[^435]

### Ch2 Q4

> Suppose Bob receives a messages signed using a digital signature scheme with Alice's secret signing key. Does it prove that Alice saw the message and chose to sign.

Well technically yes, but given how paranoid the cryptographers are we can safely assume that Alice was kidnapped and was forced to sign this message. _sigh_

### Ch2. Q6

> Suppose a chosen-ciphertext attacker cannot recover the secret decryption key for an encryption scheme. Does this mean the encryption scheme is secure?

Nope. Keys aren't always required to attack on ciphers.

### Ch 2 Q7

> Consider a symmetric-key crypto system in which cryptographic keys are randomly selected from the set of all n-bit strings. Approximately what should n be in order to provide 128 bits of security against a birthday attack.

Generating 2^128 keys requires n to be 256.
