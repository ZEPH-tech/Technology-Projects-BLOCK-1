
## ⭐ Activity 4: Basic System Info

### 🎯 Goal  
Use CLI commands to inspect your system.

### 📝 Tasks
1. Check your current username:
   ```bash
   whoami
   ```
2. Check disk storage:
   ```bash
   df -h
   ```
3. Check RAM usage:
   ```bash
   free -h
   ```

**Upload screenshots for every step**

### ✅ Completion notes (recorded output)

`whoami`:

```text
subham
```

`df -h` (disk storage):

```text
Filesystem      Size  Used Avail Use% Mounted on
/dev/sdd       1007G  4.2G  952G   1% /
tmpfs           3.7G   19M  3.7G   1% /tmp
C:\             476G  124G  353G  26% /mnt/c
```

`free -h` (RAM usage):

```text
               total        used        free      shared  buff/cache   available
Mem:           7.4Gi       1.4Gi       4.9Gi        22Mi       1.3Gi       6.0Gi
Swap:          2.0Gi          0B       2.0Gi
```

> Note: these outputs were captured in the WSL2 Linux terminal used for this lab.


