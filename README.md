# Socket Statistics

Become `root` user for better results:
```bash
sudo su
```

Help for getting all available options:
```bash
ss -h
```

Show TCP connections:
```bash
ss -t
```

Show all TCP connections:
```bash
ss -ta
```

Show UDP connections:
```bash
ss -u
```

Show raw sockets:
```bash
ss -w
```

Show unix domain sockets:
```bash
ss -x
```

Show DHCP sockets:
```bash
ss -d
```

Show process ID:
```bash
ss -p
ss -tp
```

Show ipv4 connections:
```bash
ss -4
ss -t4
```

Show ipv6 connections:
```bash
ss -6
ss -t6
```

Show port numbers:
```bash
ss -tn
```

Filter state:
```bash
ss -t state established
ss -t state listening
```

Show listening connections:
```bash
ss -tl
```

Show timer information:
```bash
ss -to
```

Show source or destination connections for specfic port number:
```bash
ss -t dst :22
ss -t src :22
```







