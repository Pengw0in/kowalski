# Kowalski Bot

A versatile Discord bot for message encryption, decryption, and analysis. Kowalski supports various encryption methods including Caesar Cipher, Base64, Morse code, and more.

## Features

- Multiple encryption/decryption methods
- Message hashing capabilities
- Text analysis tools
- Combo commands for layered encryption
- Salted hashing for secure data handling

## Command Prefix
All commands start with `/`

## Basic Commands

### Encryption & Decryption
- `/me` - Morse Code Encryption
- `/md` - Morse Code Decryption
- `/ce` - Caesar Cipher Encryption
- `/cd` - Caesar Cipher Decryption
- `/be` - Binary Encryption
- `/bd` - Binary Decryption
- `/he` - Base64 Encryption
- `/hd` - Base64 Decryption
- `/ve` - Vigenère Cipher Encryption
- `/vd` - Vigenère Cipher Decryption
- `/rot13` - ROT13 Cipher
- `/reverse` - Reverse Text

### Hashing & Security
- `/hashmd5` - MD5 Hashing
- `/hashsha256` - SHA-256 Hashing
- `/rs` - Random Substitution Cipher
- `/sh` - Salted Hashing
- `/aese` - AES Encryption
- `/aesd` - AES Decryption

### Analysis
- `/analysis` - Text Analysis

### Special Features
- `/combo` - Combine multiple encryption methods
  Example: `/combo ce,he HelloWorld` (Caesar Cipher + Base64)

## Examples

```
/me Hello World
Output: .... . .-.. .-.. --- / .-- --- .-. .-.. -..

/ce Hello
Output: Khoor
```

## Support
For support or issues:
- Discord:  [lohithsrikar00](https://discordapp.com/users/876134632905666621)
- Email: lohithsrikar679@gmail.com

## Credits
Template design by [HTML5 UP](http://html5up.net)
