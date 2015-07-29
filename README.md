# docker-nmap
NMap 6.49BETA4-1 Dockerized.

This is a dockerized version of Nmap.

The easiest way to use this image as a replacement for an installed version of `nmap` is to create an alias.

```bash
alias nmap='docker run -it --rm golden/nmap'

nmap -p 443 -v -A github.com
```
