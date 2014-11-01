thep
====

This project aims to provide homomorphic encryption libraries to developers so they can in turn create privacy and confidentiality aware software. See http://en.wikipedia.org/wiki/Homomorphic_encryption for more information on the general capabilities of this form of encryption.

Currently the code implements the Paillier cryptosystem (http://en.wikipedia.org/wiki/Paillier_cryptosystem) in Java, along with its homomorphic operations and key generation. Saving/transporting keys and encrypted integers can be accomplished using methods inherited from Serializable.

We have also implemented the GT-SCOT protocol from http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.59.9123&rep=rep1&type=pdf.

In the future we hope to implement more cryptosystems and port the library to other languages. For questions, comments, suggestions, or anything else, contact me (mikec AT cs DOT utah DOT edu). I would also be interested in collaboration on any projects you might like to use thep for, so contact me directly for that too.
