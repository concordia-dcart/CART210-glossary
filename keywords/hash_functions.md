## Hash Functions

A hash function, used within code, is meant to turn numerical or string instances, or "keys", into usable buckets of data, known as "hashes". When you hash a message, it takes your file or message of any size, runs it through a mathematical algorithm, and spits out an output of a fixed length. 
Usually implemented to fulfill a form of a hash table, it operates three various functions within itself:
- It converts the keys into fixed lengths using ADD or XOR
- It rearranges the bits to uniformly disturbute them over the keyspace
- Generate a hash that is equal to or less than the network's target hash [^Frankenfield23whatishash]



In laymans terms, it stores each value into a book of sorts, storing it then in a bookshelf for easy keeping, by assigning the often times complex wording scheme into a simple letter, less than or equal to the amount of space the bookshelf has.

Used in other languages such  as C#, PHP, Java, and Python, it is often times implemented by default for a variety of those listed above, and can be overridden to suit the users needs for that specific program or project.

As well, it is used in certain types of modern cryptography, mostly within banks for making sure no fraudulance can happen within. Based on the Security by Obscurity Approach, the whole cryptosystem is communicating securely while maintaining a high level of privacy. [^Ahmed22hashfunctionapplications] Even though hash functions have many applications in modern cryptography, they
are perhaps best known for the important role they play in the practical use of digital signatures. [^Paar70hashfunction]

[^Frankenfield23whatishash]:Frankenfield, Jake. 2023. “What Is a Hash? Hash Functions and Cryptocurrency Mining.” _Investopedia_. Last Modified May 28, 2023. www.investopedia.com/terms/h/hash.asp. 
[^Paar70hashfunction]:Paar, Christof, and Jan Pelzl. 1970. “Hash Functions.” _SpringerLink, Springer Berlin Heidelberg_. Last Modified January 1, 1970. link.springer.com/chapter/10.1007/978-3-642-04101-3_11. 
[^Ahmed22hashfunctionapplications]:Ahmed, Haifaa. 2022. _A review of hash function types and their applications_. Wasit Journal of Computer and Mathematics Science, vol. 1, no. 3, pp. 75–88. https://doi.org/10.31185/wjcm.52.
