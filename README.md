# ufw-applications
Extra ufw app profiles

## UFW Rules

how to create your own application file, you only need to know that it is using windows INI file format.

```
[appname]
title=1-liner here
description=a longer line here
ports=1:10,30/tcp|50/udp|53
```

The ports line can specify multiple ports, with /udp or /tcp, to limit the protocol, otherwise it defaults to both. You have to split the protocol sections up with |.
