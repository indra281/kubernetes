if docker failed to start. start docker in debug mode and check the status 
```
sudo dockerd --debug
```
 if docker failed to start due to iptabled not found then run docker with iptables": false
 create or edit /etc/docker/daemon.json
```
vi /etc/docker/daemon.json
```
add this 
```
 {
"iptables": false
}
```

and then start docker 