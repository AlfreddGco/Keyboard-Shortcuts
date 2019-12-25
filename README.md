# Keyboard-Shortcuts
C++ program for auto-writing with custom keyboard shortcuts in Linux systems

## Dependencies
The only dependency needed is libxtst-dev which you can install manually or using make file:
```
make install
```
## Compiling
```
make
```
## Install as service
```
sudo make install_service
```
## Usage
For adding, removing and showing shortcuts run the next commmand after installing as service:
```
kbd-shortcuts --help
```

Super + ctrl will make program start listening for command and start autowriting

Program is closed by killing the process or by stopping the service with:
```
sudo systemctl stop kbd-shortcuts.service
```

## To do
- Support for MacOS
- Support for most languages
