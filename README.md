# Pipe SSH
## Build command pipelines that spans multiple servers
### parses your ~/.ssh/conf and updates your ~/.bashrc with aliases to each node
Create aliases:
```
./pipe-ssh init
```
Usage:
```
echo ls -l | node-0-0 | lolcat
# Sends to^ ^this node  ^back to localhost

```
Uninstall:
```
./pipe-ssh clean
```