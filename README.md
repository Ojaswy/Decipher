# Decipher
This is a Python script used to decrypt Substitution, Caesar, and Vigenère Ciphers.
It takes in the name of a file containing encrypted text and, using frequency analysis, decrypts into English plaintext.

CAESAR: python decrypt.py MyFile.txt CAESAR

VIGENERE: python decrypt.py MyFile.txt VIGENERE 10
Here, 10 represents the length of the key replace that with the required length

SUBSTITUTION: python decrypt.py MyFile.txt SUBSTITUTION True
 "True" dictates whether this is the first time running. The substitution mapping will be saved/output to the "alphabets.txt" file.
 This is semi-automatic, so after a base frequency analysis is determined, you should change the value to "False" and
 switch around the letters in the output file.
 
 MyFile.txt: Text file which contains encrypted texts
