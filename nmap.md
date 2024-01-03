Clone https://github.com/scipag/vulscan and move the new vulscan directory to your nmap scripts directory

```script
nmap -sV --script vuln <target>
nmap -sV --script vulners.nse <target>
nmap -sV --script vulscan/vulscan.nse <target>
```