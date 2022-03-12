# Network Command

Check Node Network Interface
```bash
ip a | grep -B2 <node internal IP>
```

Check master node's MAC address
```bash
ip link show <node network interface>

# e.g.
ip link show eth0
```

Checn worker node MAC address
```bash
arp node01
```

Check Docker interface/bridge
```bash
ip link
```

Check Default Gateway IP address
```bash
ip route show default
```
Check port the **kube-scheduler** is listening on in the **controlplane** node
```bash
netstat -nplt
```

which ETCD port have more client connections established?
```bash
netstat -anp | grep etcd
```
