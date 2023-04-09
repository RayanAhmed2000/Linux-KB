## Change file permissions using chmod
```
chmod g+w <filename>
```
- similarly
```
chmod g-x,u-w,o-rx <filename>
```
- number method
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
## getfacl and setfacl
```
getfacl <filename>
```
```
setfacl -m u:rayan:rwx <filename>
```
# change user and group of a file
```
chown rayan.group1 <filename>
```
- recursively change permissions of all files inside dir1
```
chown rayan.group1 /dir1 -R
```
# umask
- mask permissions when a new file is created
- umask 0777 will give no permissions (---------) to a newly created file
```
umask 0002
```
