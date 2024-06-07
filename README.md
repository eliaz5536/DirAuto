![dirauto_logo](https://github.com/eliaz5536/DirAuto/assets/5835036/97a666c3-bb93-4ece-a752-e2574d6932f8)

# Demos 
## Automatic Directory Enumeration Scan
[![asciicast](https://asciinema.org/a/qWE7UgFr1jJ7GN0Uv2wl5LChN.svg)](https://asciinema.org/a/qWE7UgFr1jJ7GN0Uv2wl5LChN)

## Automatic VHost Enumeration Scan
[![asciicast](https://asciinema.org/a/YIa74NmdbzuezIi8Dbq3gddPi.svg)](https://asciinema.org/a/YIa74NmdbzuezIi8Dbq3gddPi)

## Automatic DNS Enumeration Scan
[![asciicast](https://asciinema.org/a/gCvMSkPseLYsUQb83SfaA2spA.svg)](https://asciinema.org/a/gCvMSkPseLYsUQb83SfaA2spA)

# DirAuto
DirAuto is a customizable directory reconnaissance tool that automates enumeration of subdomains, ideal for penetration testing environments and network scanning.

# Installation
Your machine must be up-to-date installing the latest available packages
```
sudo apt-get update
```

If you want to ensure that all of these packages are installed, perform those following commands instead:
```
sudo apt-get install python python2 python3 python3-pip pip pipx
```

These following tools need to be installed and put in /opt directory in order to utilize the following script:
| [GoBuster](https://github.com/OJ/gobuster) | [FFuF](https://github.com/ffuf/ffuf) | [FeroxBuster](https://github.com/epi052/feroxbuster) | [Dirsearch](https://github.com/maurosoria/dirsearch) | [Dirb](https://github.com/v0re/dirb) |
|----------|------|-------------|-----------|------|

You will also need to install the following wordlists in order to execute one of the following
```
sudo apt-get install seclist
```

# Requirements
You can utilize the bash script by downloading the git clone by the following:
```
# Clone the following repository
https://github.com/eliaz5536/DirAuto.git # Clone repository

# Access the repository and change file permission of the script to be executable
chmod +x dirauto

# Launch DirAuto
./dirauto
```
# Usage 
```

┳┓•  ┏┓     
┃┃┓┏┓┣┫┓┏╋┏┓
┻┛┗┛ ┛┗┗┻┗┗┛

Directory Enumeration Automator with Gobuster, FFuF, Feroxbuster, DirSearch & Dirb
 
Usage: dirauto [dir / vhost / subdomain] [-u, --url] [--usage] [-h, --help] [-u, --url] [-x, --extensions] [-c, --status-codes] [-d, --dir] [-v, --vhost] [-s, --subdomain] [-t, --threads] [-w, --wordlist] [--check] [-i, --install]
 
Options:
  --usage                       Show usage information
  -h, --help                    Show help message
  -u, --url                     Specify target URL
  -x, --extensions              Specify extensions
  -c, --status-codes            Specify status codes
  -e, --extension-rate          Specify extension rate
  -t, --threads                 Specify number of threads
  -w, --wordlist                Specify wordlist
  --check                       Check if repositories are installed
  -i, --install                 Install repositories
 
Modes:
  dir                           Directory Mode
  vhost                         Virtual Host Mode
  subdomain                     Subdomain Mode

```
