Lab 1: John the Ripper and Johnny
John the Ripper cracked the PDF password through Johnny, its graphical front end.
1.  Installed John the Ripper and the Johnny GUI on Windows, then pointed Johnny to john.exe.
2.  Extracted the hash ($pdf$...) from the locked PDF and saved it as hash1.txt.
3.  Loaded the file into Johnny and started a new attack.
4.  Johnny recovered the password, which opened the PDF.
Lab 2: Networkwalks Hash Calculator and Password Cracker
The same PDF was cracked again using two browser-based tools, with nothing to install.
1.  Uploaded the locked PDF to the Hash Calculator to extract its hash.
2.  Pasted the full hash into the Password Cracker and started the dictionary attack.
3.  The tool tried passwords from its built-in list until it found a match.
4.  Entered the recovered password and the PDF opened.
Key takeaways
• Encryption is two-way (reversible with a key), while hashing is one-way.
• Dictionary attacks find common passwords almost instantly.
• Strong passwords are long, unique and mixed, ideally kept in a password manager.
Disclaimer
This work was done in a controlled lab environment on files provided for training. It is for educational purposes only
