# Comandos útiles

## Reconocimiento
```bash
nmap -sC -sV -A <IP>
ss -tulpn
netstat -ano
```

## Web
```bash
curl -I http://<IP>
whatweb http://<IP>
gobuster dir -u http://<IP> -w /usr/share/wordlists/dirbuster/directory-list-2.3-medium.txt
```

## Escalada
```bash
sudo -l
find / -perm -4000 2>/dev/null
ls -l /etc/cron*
```

## Forense
```bash
file *
strings *
md5sum *
sha256sum *
```
