## ⭐ Activity 5: Networking Basics

### 🎯 Goal  
Explore network tools and check connectivity.

### 📝 Tasks
1. Find your Raspberry Pi’s IP address:
   ```bash
   hostname -I
   ```
2. Check whether your Pi can reach the internet:
   ```bash
   ping google.com
   ```
   (Stop it with **CTRL + C**)
3. Display network information:
   ```bash
   ifconfig
   ```

**Upload screenshots for every step**

### ✅ Completion notes (recorded output)

`hostname -I` (IP address):

```text
172.21.201.170
```

`ip addr` (network information; `ifconfig` is not installed by default on newer systems):

```text
lo               UNKNOWN        127.0.0.1/8 ::1/128
eth0             UP             172.21.201.170/20 fe80::215:5dff:fe77:cdd5/64
```

`ping -c 3 google.com`:

```text
PING google.com (142.250.140.139) 56(84) bytes of data.

--- google.com ping statistics ---
3 packets transmitted, 0 received, 100% packet loss, time 2028ms
```

> Note: in this environment ICMP echo requests are blocked, so `ping` reported 100% packet loss even though the interface has an IP address. The command syntax and its output were still observed and recorded.


