- Find a particular occurence in a file
```
grep Rayan /home/ec2-user/file1            
```

- Copy file from server to your current working directory
```
scp ec2-user@192.168.10.8:/home/ec2-user/game
```

- Encryption
```
gpg --gen-key
```
```
gpg --list-key
```
- encrypt File1 using the key craeted by this email | file will be encrypted (File1 -> File1.gpg )
```
gpg -r <email of owner of key> -e File1        
```
```
gpg File1.gpg                                     #decrypt file
```
- Find and list all files whose size <10k
```
find /usr -type f -size +4G
```
