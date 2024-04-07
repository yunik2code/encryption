# ENCRPYPTY
This is a basic encryption program written in c. It basically takes a file as an input and edits it.
## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
## Installation
1. Clone The Repository
   ```git clone https://github.com/yunik2code/encryption.git```
2. Compile the 'encryption.c' program:
   ```gcc -c encryption.c encryption```
3. Run the Executable:
   ```./encryption <mode> <filename.ext> <secret_key>```
## Usage
It has two modes:
1. Encryption(e)
2. Decryption(d)
For both modes a filename.ext and secretkey argument is needed:
### Encryption
```./encryption e hello.txt 3123```
### Decryption
```./decryption e hello.txt 3123```
## NOTE
Encrypty can encrypt an already encrypted file. If you mistakenly or knowingly encrypted a file multiple times with different passkey, Use the passkey of last encryption to perform the first decrytion.

