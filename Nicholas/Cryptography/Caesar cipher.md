---
Last time checked: 2024-02-25
Complete: true
aliases:
---
# Caesar cipher
***
###### tags: #Cryptography 
***
>[!dsn]+ 
>The *Caesar cipher*, named of Julius Caesar, encrypts a message by shifting each of the letters down three positions in the alphabet, wrapping back around to $A$ if the shift reaches $Z$.^[[[Jean-Philippe Aumasson - Serious Cryptography - A Practical Introduction to Modern Encryption.pdf#page=26|Jean-Philippe Aumasson - "Serious Cryptography - A Practical Introduction to Modern Encryption" p.2-3]]]
>![[Pasted image 20240225182130.png]]

>[!example]+ 
>For example, $ZOO$ encrypts to $CRR$, $FDHVDU$ decrypts to $CAESAR$, and so on.

>We can make the Caesar cipher more secure, but even if we change the shift it is super easy to break, as we can check all $25$ possible shifts, until the decrypted message makes sense.
***
#### Keywords
- [[Encryption]],
#### Possibly related
- 
***
#### Sources:
