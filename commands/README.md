# Useful Commands

This folder contains commonly used commands for the tools used during this project.

## Nmap

```bash
nmap -sS -sV 10.0.2.15
nmap -O 10.0.2.15
```

## Wireshark Filters

```
http
dns
tcp.port == 80
ip.addr == 10.0.2.15
```

## Snort

```bash
snort -A console -q -c /etc/snort/snort.conf -i eth0
```
