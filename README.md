![dirauto_logo](https://github.com/eliaz5536/DirAuto/assets/5835036/97a666c3-bb93-4ece-a752-e2574d6932f8)

# Demos 
## Automatic

### Automatic Directory Enumeration Scan
[![asciicast](https://asciinema.org/a/qWE7UgFr1jJ7GN0Uv2wl5LChN.svg)](https://asciinema.org/a/qWE7UgFr1jJ7GN0Uv2wl5LChN)

### Automatic VHost Enumeration Scan
[![asciicast](https://asciinema.org/a/YIa74NmdbzuezIi8Dbq3gddPi.svg)](https://asciinema.org/a/YIa74NmdbzuezIi8Dbq3gddPi)

### Automatic DNS Enumeration Scan
[![asciicast](https://asciinema.org/a/gCvMSkPseLYsUQb83SfaA2spA.svg)](https://asciinema.org/a/gCvMSkPseLYsUQb83SfaA2spA)

## Custom Commands
```
<insert asciinema player to show customized execution of each enumerator performed with customized settings>
```



# DirAuto
DirAuto is a basic directory reconnaissance tool that automates enumeration of directories present in existing websites, which is ideal for penetration testing environments and network scanning.

This tool performs port scans and service detection to perform further enumeration scans using different third-party tools.

It performs **no automated exploitation**.

# Installation
Requirements of utilizing this tool must be met by installing the latest available packages
```
sudo apt-get update
```

If you want to ensure that all of these packages are installed, perform those following commands instead:
```
sudo apt-get install python python2 python3 python3-pip pip pipx
```

These following tools need to be installed and put in /opt directory in order to utilize the following script:
```
gobuster
ffuf
feroxbuster
dirsearch
dirb
```

You will also need to install the following wordlists in order to execute one of the following
```
sudo apt-get install seclist
```

You can utilize the bash script by downloading the git clone by the following:
```

```

Make sure you provide the linux permission to execute the file before launching the bash script:
```
chmod +x dirauto
```

Launch NetAuto bash script file by doing the following
```shell
./dirauto -u <TARGET_URL_ADDRESS>
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

# Results
The following results of these scans will produce NMAP directory and the rest of enumeration programs for each of the following ports through its name that will store and output all enumeration results of specified protocols through either -oN flag from NMAP or use tee to output the results into specified location 
```
show file location here and directory of how it is performed
```
