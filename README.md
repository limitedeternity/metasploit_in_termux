# Metasploit Framework 6 in Termux

![Metasploit 6 running](https://i.imgur.com/yLFQhvP.png)

## How to install:
```bash
$ pkg install wget
$ wget https://raw.githubusercontent.com/limitedeternity/metasploit_in_termux/master/1_blacktermux.sh
$ wget https://raw.githubusercontent.com/limitedeternity/metasploit_in_termux/master/2_metasploit.sh
$ chmod +x 1_blacktermux.sh
$ chmod +x 2_metasploit.sh
$ ./1_blacktermux.sh -i
$ ./2_metasploit.sh
```
## After install, run from terminal
```bash
# Start postgresql
./postgresql_ctl.sh start

# And run msfconsole
msfconsole
```
