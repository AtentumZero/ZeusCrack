# ZeusCrack
A simple command-line hash cracking tool that takes in a hash value then cross-references it with a user-provided wordlist by hasing every word in the wordlist and checking to see if the hashed value matches with the hash it's meant to crack.

Supported Hash Types: (-t option)
md5, sha1, sha224, sha256, sha384, sha512"

Options: -h (Hash) -t (Hash Type) -w (Wordlist) -v (Verbose)"

Example usage: ./Zeus-Cracker.py -h <hash> -t md5 -w file.txt"
  
Expected Wordlist format is:
  
  Test
  Test123
  Password!
