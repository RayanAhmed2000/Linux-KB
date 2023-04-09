## Change file permissions using chmod
```
chmod g+w <filename>
```
- similarly
```
chmod g-x,u-w,o-rx <filename>
```
```
chmod 777 <filename>
```
- assign permissions of user to group
```
chmod g=u <filename>
```
- recursively grant permissions to files inside a directory
```
chmod -R 777 /home/rayan/dir1
```
