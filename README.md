GROK3 Description:

SeedMaker - A Cryptographically Secure BIP-39 Seed Phrase Generator and Validator
=============================================================================
Overview:
SeedMaker is a Python application built with Kivy that generates and validates 
BIP-39 seed phrases (12 or 24 words) used for cryptocurrency wallets, particularly 
Bitcoin. It adheres to the BIP-39 standard, ensuring secure entropy generation, 
checksum calculation, and wordlist mapping using the official 2048-word list.

Key Features:
- Generate 12 or 24-word seed phrases from random entropy or user input (bits, hex, dice rolls).
- Validate existing seed phrases with checksum verification.
- Provide detailed cryptographic breakdowns (entropy, checksum, binary, etc.).
- User-friendly interface with options to copy, hide, or clear seeds.
- Help and About screens for education and attribution.

Security Enhancements:
- Uses os.urandom() for cryptographically secure random number generation.
- Avoids unnecessary external calls or suspicious behaviors that might trigger antivirus.
- Ensures proper file handling and resource cleanup to avoid memory leaks or flags.
- No network activity, reducing risk of being flagged as malicious.

UI Enhancements:
- Removed Validate Seed button (auto-validation).
- Added Paste button at top of input fields.
- Single message panel with red (error) or light-to-darker green (valid) colors.
- Simplified messages to "Invalid X Word Seed Phrase" or "Valid X Word Seed Phrase".

Dependencies:
- Python 3.13
- Kivy (GUI framework)
- PyInstaller (for creating .exe)
- wordlist.txt (BIP-39 English wordlist, 2048 words, must be bundled with executable)

Usage:
- Run directly with Python: `python seedmaker.py`
- Or compile to .exe with PyInstaller: 
  `pyinstaller -F -w --add-data "wordlist.txt;." seedmaker.py`

Notes:
- Ensure wordlist.txt is in the same directory as the script or bundled correctly.
- For maximum security, use offline on an air-gapped machine.
- Never share seed phrases online or with untrusted parties.

SeedMaker - Cryptographically Secure BIP-39 Seed Phrase Generator and Validator
=============================================================================



Developer description: 
# SeedMaker
Create SeedMaker folder on desptop add:
SeedMaker.py 
Wordlist.txt

Install Kivy 
Install Python

Double click on SeedMaker.py file to open APP.

Description:
Python Script to run in Windows Terminal Creates a Kivy of SeedMaker APP for Bitcoin 12/24 Word Seed Phrase Generation. .   


This builds a APP on your PC using Kivy. It was built by GROG3 Beta FREE Demo Version AI on x.com. I was just having a play this is what GROK3 came up with, i had to tell it what to do like 40 different rebiulds to get it right and functioning. It was an adictive and fun way to biuld a program with no knowledge of coding python scriptin langauge. 

Welcome to SeedMaker Help!
- One click SeedMaker Makes a 128 or 256 random dice rolls Valid 12/24 Words Seed Phrase :
- Input your own 128 or 256 Bits (0101000101010111): And let SeedMaker generate you seed.
- Do your own 128 or 256 Dice Rolls one at a time or hold the button down for repetitive rolls: Roll bits, make seed.
- Hex: Type hex 32 or 64, make seed. 
- Enter your own Words and check if it a valid seed: Type seed, validate.
- Hide/Show: Toggle seed view.
- Copy: Copy seed to clipboard.
- Clear: Reset the screen.
- Use offline for security!
- Lots of details about the seed, from all the entropy shown in binary a big long 128 bit or 256 binary like this 1010101010111101010101010, the words converted to 11 binary bits, the BIP39 words in decimal numbers, the decimal number of the  entropy, the checksum hex, binary and the checksum word. All the gory details. 

Instructions to use the Python code>>>

To use it copy the entire code and paste into a regular notepad on Windows PC or Laptop, i haven't tried Apple Mac or Linux but it should work and save the notepad file as SeedMaker.py make sure it is note saved with .txt extension it should be file_name.py so it opens with python. Trick:  If you double click on the file SeedMaker.py it auto opens the APP and it will be instantly usable on screen to have play with.  

You need to have Python installed on you computer and i think Kivy as well. Sorry i am not fully confident with all this as i just followed the directions of GROK to do it all. Search how to make a Kivy app using a Python code file in Google or GROK or another AI and it will talk you through the step even if you don't know how it's amazing and easy if i could do it never done it before and in 48hrs this whole program was built.
