# Monoalphabetic_Cipher
Monoalphabetic crypting/decrypting script written in plain Javascript. 


Javascript functions can be found in .js file, whilst there also is an example usage in a web page as in .html file. 

This monoalphabetic cipher uses the 26 letters of English alphabet. First shuffles the places of alphabet's characters, then changes the plaintext characters with the matching characters in the shuffled alphabet. Shuffled alphabet is given as the "Key".

Example Usage:

Plaintext: "Example"
Shuffled Alphabet, a.k.a Key: "OKBNSHDPEARMGYXJVWUFCTLZIQ"

First character of the plaintext, "E" is the 5th character(Index = 4) in English alphabet, in the shuffled alphabet, 5th character is "S". Therefore "E" is changed with "S"

Second character, "X" is the 24th(Index = 23) character, which matches with "Z" in our shuffled alphabet. 
Therefore "X" is changed with "Z"

This process is done for every character in plaintext, 
and the ciphered text is: "SZOGJMS"

White spaces and non-alphabet characters will be neglected, so they can be used inside plaintext without further problems.
