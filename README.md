# Fancy uptime
A fancy uptime reader that makes a nicer output than the uptime command.

## Usage
```bash
fuptime
```

## Build
### Dependencies
- gcc
- make
```bash
sudo apt install gcc make
```
### Build using make
```bash
make compile
```
### Manual build
```bash
gcc -o fuptime fuptime.c
```

## Installation
```bash
git clone https://www.github.com/awesomelewis2007/fancy_uptime
cd fancy_uptime
make
mv fuptime scripts/fuptime
cd scripts
sudo bash install_fuptime.sh
```
## Uninstallation
```bash
cd scripts
sudo bash uninstall_fuptime.sh
```