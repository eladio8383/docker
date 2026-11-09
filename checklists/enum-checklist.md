# Checklist de enumeración

## Enumeración general
- `whoami`
- `id`
- `hostname`
- `uname -a`
- `ip a`
- `ss -tulpn`
- `ls -la`

## Enumeración web
- `curl -I`
- `whatweb`
- `gobuster`
- `nikto`

## Enumeración de sistema
- `sudo -l`
- `find / -perm -4000`
- `/etc/passwd`
- `/etc/shadow`
- `crontab -l`

## Enumeración de red
- `arp -a`
- `netstat -ano`
- `iptables -L`
- `route -n`
