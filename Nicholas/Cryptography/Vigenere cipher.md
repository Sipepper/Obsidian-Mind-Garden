---
Last time checked: 2024-02-25
Complete: true
aliases:
---
# Vigenere cipher
***
###### tags: #Cryptography 
***
>[!dsn]+ 
>The Vigenere cipher is similar to [[Caesar cipher]] but instead of constant shift, the shift depends on *key*, the collection of letters that represent numbers based on their position in the alphabet.^[[[Jean-Philippe Aumasson - Serious Cryptography - A Practical Introduction to Modern Encryption.pdf#page=27|Jean-Philippe Aumasson - "Serious Cryptography - A Practical Introduction to Modern Encryption" p.3]]]
>![[Pasted image 20240225183215.png]]
 
>[!example]+ 
>For example, if the key is $DUH$, letters in the plaintext are shifted using the values $3$, $20$, $7$. So the word $CRYPTO$ would encrypt to $FLFSNV$ using $DUH$ as the key; $C$ is shifted three positions to $F$, $R$ is shifted $20$ position to $L$ and so on.

>The Vigenere cipher is more secure that the [[Caesar cipher]] by it's fairly easy to break. It can be done in the following steps:
>1. Figure out the key's length, for example $THEY DRINK THE TEA$ with key $DUH$ encrypts to $WBLBXYLHRWBLWYH$. This suggests that the same three-letter word was encrypted using the same shift values, producing $WBL$ each time.
>2. Determine the actual key using a method called [[Frequency analysis]], which exploits the uneven districution of letters in languages. For example, in English, $E$ is the most common letter, so if you find that $X$ is the most common letter in a ciphertext, the the most likely plaintext value at this position is $E$.
***
#### Keywords
- [[Encryption]],
#### Possibly related
- 
***
#### Sources:
