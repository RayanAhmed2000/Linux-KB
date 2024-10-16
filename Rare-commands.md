# init 
- is used to shut down/reboot the system
```
init 0  #shutdown
init 6 #reboot
```
# Shuf
- randomly select lines from a file or generate random numbers
```
shuf -n 5 abc.txt       # select 5 random lines from abc.txt
shuf -i 1-100 -n 2      # select 2 random numbers between 1-100
```
# yes
- automatically answer yes to all promts
```
yes | sudo apt upgrade
```
# rev
```
echo "hello world" | rev
dlrow olleh
```
