Lab3 Questions/Answers
=======================

- **Q.** For Lab 3 are we only implementing linear probing, or do we implement quadratic probing and double hashing as well?

- **A.**  You have to calculate collisions for all 3 probings and output them.
So you have implement all 3 probings otherwise how you will know number of collisions?
You have to print tables for all probings.


- **Q.** I have one more question. What hash function are we using, is it, hash(x) % table size, or is it, (hash(key) = (key>>8)|((key&0xff)<<16))?

- **A.** The first index is calculated as hash(x) % table size. For this Example hash(x) = x;
Hash function for Lab3 is (hash(key) = (key>>8)|((key&0xff)<<16))
I provided pdf file, you just need to do similar using different input files.


