# The RSA cryptosystem
sources: 

- RSA patent: https://www.google.com/patents/US4405829, 
- basic paper on RSA tech: http://www.math.uchicago.edu/~may/VIGRE/VIGRE2007/REUPapers/FINALAPP/Calderbank.pdf

## Intro: why talk about RSA? 
- RSA is backbone of most distributed systems as it provides both a way to encrypt data as to validate the source of data
- RSA is named after 3 inventors, reference the patent

## Basics:
- in RSA cryptosystem, need for a pair of hashes also called keys
- are algorithmically generated so that they are cryptographically connected: data encrypted with one hash can only be decrypted with the other hash and visa versa
- one of these keys can be publicly broadcoasted, so everyone knows that this key is connected to your identity. => called the public key
- one key is to be held privately, very important nobody except you knows this key => called the private key

## use case 1: encryption
- first use case is encryption: if Alice wants to send a message to Bob, she can encrypt the message with Bob's public key and send the encrypted message over any insecure network (eg. internet, email, messenger pigeon)
- only Bob will be able to decrypt the message as only Bob has the private key corresponding to the key used for the public encryption

## use case 2: source validation
- another use case is to validate the source of some piece of information: if Alica wants to broadcast a message to the world, but needs to prove that the message actually came from her => encrypt the message with her public key. The encrypted message can only be decrypted with Alice's public key => only Alice could have encrypted it. In this case, we call this encryption a "signature": Alice "signed" the message.
- it is quite common to first sign a message yourself (ie. encrypting with own private key) and then encrypt the message with the public key of the recipient. => only recipient can decrypt and the recipient can then validate the origin of the message

## conclusion
- the RSA cryptosystem removes the need for a third party to either securely transmit a message of to validate the origin of a message.


