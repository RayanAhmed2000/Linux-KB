# Port/service running check
```
lsof -n -i -P | grep LISTEN
```
# Delete Log files greater than 1 GB
```
find . -maxdepth 1 -type f -name "*.log" -size +1G -exec rm -v {} \;
```
