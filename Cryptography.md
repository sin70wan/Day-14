What is Cryptography? 
● Cryptography is the science of secret, or hidden writing 
● Crypto => Hidden/Secret | Graphy => Writing 
● Used to secure your data/text. 
● It has two main Components:
   a. Encryption
    i. Practice of hiding messages so that they can not be read by anyone other than the intended recipient 
   b. Authentication & Integrity 
     i. Ensuring that users of data/resources are the persons they claim to be and that a message has not been altered Encryption Cipher 
● Cipher is a method for encrypting messages 
● Encryption algorithms are standardized & published 
● The key which is an input to the algorithm is secret ● Key: is a string of numbers or characters 
● If same key is used for encryption & decryption the algorithm is called symmetric 
● If different keys are used for encryption & decryption the algorithm is called asymmetric
Substitution Ciphers
Caesar Cipher is a method in which each letter in the alphabet is rotated by three letters 
Substitution Cipher by Using a key to shift alphabet
Replacing the letters by 1 shift we can get different rotations. websites like rot encoding 
Asymmetric Encryption 
● Uses a pair of keys for encryption 
○ Public key for encryption 
○ Private key for decryption
Types of asymmetric enc. 
● Two most popular algorithms are RSA & El Gamal
         3 Terms of Cryptography 
    1) Encoding/ decoding 
         a) This is a method of creating Cipher text with our using any key 
         b) This can be done by doing math on the given input/substitution 
         i) Examples: base64,base32,rot… 
    2) Encrypting/Decrypting 
           a) This is method of creating Cipher text with keys.
         b) To decrypts this kind u need to have the private key i) Example: DES,AES,RSA 
    3) Hashing 
          a) This is a method of creating Cipher text with respect to a created hash 
          b) To reverse the hash, you just search for some match, you don't decrypt/decode it. 
          c) Salt: is a random string used for data modification for password protection. i) Example: MD5,sha254,...
  ● Tools: 
  ○ hashid
      ■ hashid <hash>
   ○ Cyber chef (web)
   Python for cryptography 
   ● We can use programming to do tools that can do our own encryption and encoding hash type
   Obfuscation: In software development, obfuscation is the act of creating source or machine code that is difficult for humans or computers to understand.