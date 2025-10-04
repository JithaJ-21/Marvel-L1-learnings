* A **cipher** is a method used to hide a message by changing its letters or structure in some systematic way. The goal is that only someone who knows the method (or key) can read the original message.
* In **Caesar Cipher**, each letter in the message is shifted by a certain number
* **Vigenère Cipher** is an improvement over Caesar cipher; instead of using one shift, it uses a word (key) to decide how each letter is shifted
* In **Substitution Cipher**, each letter is replaced with a different letter, according to a secret mapping

The ciphers above are reversible; if we know the method (key), we can get back the original message

But **SHA256** is a hashing algorithm, not a cipher. It takes any message and creates a unique, fixed-length fingerprint (called a hash), which we cannot reverse.

* **Symmetric Key** Encryption: one key is used to encrypt and decrypt; Both sender and receiver must share the same key secretly.
* **Asymmetric Key** Encryption(Public &amp; Private Keys):
**Public Key**: Can be shared with anyone
**Private Key**: Must be kept secret
How it works: we encrypt a message with someone’s public key which only their private key can decrypt.
* **RSA** is a popular type of asymmetric encryption. It stays secure by using really large prime numbers that no one can factor easily.

For instance, consider 2 prime nos. p=61 and q=53. Let n=p*q=3233. This n is a part of the public key and if someone sees this n, they will have to figure out the 2 primes used to make it, which will be quite difficult...esp. for huge primes, it will be practically impossible.
