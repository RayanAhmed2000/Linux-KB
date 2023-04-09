
# Encryption
```
gpg --gen-key
```
```
gpg --list-key
```
# encrypt File1 using the key craeted by this email | file will be encrypted (File1 -> File1.gpg )
```
gpg -r <email of owner of key> -e File1        
```
```
gpg File1.gpg                                     #decrypt file
```
