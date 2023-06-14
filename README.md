# File path

Linux/Unix-liked/macOS:

```
/etc/resolv.conf
```

Windows:

```bash
# This file can be used to configure the mapping between local hostnames and IP addresses.
%windir%\system32\drivers\etc\hosts
# The DNS cache file under the directory. This file is used to store cache data during DNS resolution, and if you need to empty the DNS cache, you can delete this file.
%windir%\system32\dns\
```

# Great DNS

```bash
# Google DNS
nameserver 8.8.8.8
# Domestric DNS
nameserver 114.114.114.114
# Bilibili DNS
nameserver 223.5.5.5
nameserver 223.6.6.6
```