A Python script that finds which candidate password matches a stored hash (MD5/SHA...), then XOR-decrypts flag.enc with that password and prints the flag.

How it works (3 steps)

Load candidate passwords from pos_pw_list in a Python file.

Hash each candidate and compare to hash.bin.

On match, XOR-decrypt flag.enc and print plaintext.

Files

challenge.py (or file with pos_pw_list)

flag.enc (encrypted bytes)

hash.bin (stored hash)

Run
