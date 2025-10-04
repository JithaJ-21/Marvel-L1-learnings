## Nmap scan techniques

| Scan Type    | Command | Protocol | Privilege Needed | Speed  | Stealth  | Description                              |
| ------------ | ------- | -------- | ---------------- | ------ | -------- | ---------------------------------------- |
| SYN Scan     | `-sS`   | TCP      | Root/Admin       | Fast   | Stealthy | Sends SYN only (half-open)               |
| Connect Scan | `-sT`   | TCP      | Normal User      | Medium | No       | Full 3-way handshake                     |
| UDP Scan     | `-sU`   | UDP      | Root/Admin       | Slow   | Moderate | Sends UDP probes, waits for ICMP replies |


## Nmap commands

| Nmap command | What it does |
|-------|---------|
| -sP/-sn | Host discovery only—determines which targets are up; skips port scanning |
| -Pn | Skips host discovery—treats all targets as up and goes straight to port scanning (Use this when targets block ICMP/ping or you suspect host discovery will fail) |
| -A | “Aggressive” all-in-one scan—enables OS detection, version detection, default NSE scripts and traceroute |
| -p | Specify ports to scan.Use when: You want to limit scan time or target specific services |
| -iL<file> | Read targets from a file |




