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
