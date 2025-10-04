| Nmap command | What it does |
|-------|---------|
| -sP/-sn | Host discovery only—determines which targets are up; skips port scanning |
| -Pn | Skips host discovery—treats all targets as up and goes straight to port scanning (Use this when targets block ICMP/ping or you suspect host discovery will fail) |
| -A | “Aggressive” all-in-one scan—enables OS detection, version detection, default NSE scripts and traceroute |
| -p | Specify ports to scan.Use when: You want to limit scan time or target specific services |
| -iL<file> | Read targets from a file |
