![dirauto_logo](https://github.com/eliaz5536/DirAuto/assets/5835036/97a666c3-bb93-4ece-a752-e2574d6932f8)

# Demo
[![asciicast](https://asciinema.org/a/Ux26WNgdmIuEr9drhCRjmS5Li.svg)](https://asciinema.org/a/Ux26WNgdmIuEr9drhCRjmS5Li)

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
You will also need to install SecList in order to access extensive list of wordlists
```
sudo apt-get install seclist
```
These following tools must be installed in order to use the script:
| [GoBuster](https://github.com/OJ/gobuster) | [FFuF](https://github.com/ffuf/ffuf) | [FeroxBuster](https://github.com/epi052/feroxbuster) | [Dirsearch](https://github.com/maurosoria/dirsearch) | [Dirb](https://github.com/v0re/dirb) |
|----------|------|-------------|-----------|------|
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
 
Usage: dirauto [modes] [options]
 
Options:
  --usage                                               Show usage information
  -h, --help                                            Show help message
  -u, --url                                             Specify target URL
  -x, --extensions                                      Specify extensions
  -p, --programs                                        Specify enumeration programs
  -c, --status-codes                                    Specify status codes
  -w, --wordlist                                        Specify wordlist
  --check                                               Check if repositories are installed
 
Modes:
  dir                                                   Directory Mode
  vhost                                                 Virtual Host Mode
  subdomain                                             Subdomain Mode
 
Enumeration Programs:
  gobuster                                              Directory/File, DNS and VHost busting tool written in Go
  ffuf                                                  Fast web fuzzer written in Go
  feroxbuster                                           A fast, simple, recursive content discovery tool written in Rust
  dirsearch                                             Web path scanner
  dirb                                                  Web content scanner
 
Filter Options:
  -fs, --filter-status <status_codes>                   Filters HTTP status codes
  -fl, --filter-lines <line_count>                      Filters line count
  -fs, --filter-size <content_size>                     Filters content size
  -fw, --filter-words <word_count>                      Filters word count

```
