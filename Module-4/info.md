### ZIP Password bruteforcer

No need for new modules to install. Rationale of the code. 
Python libraries: zipfile, argparse
Password protected archive.zip + passlist.txt

#### How it works:
1. Open the password file
2. Line by line: try each word as password for archive.zip
3. If word = correct password, print "Success"
4. If password not found, print "Password not found".
5. 
