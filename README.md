# WASLabs
Setup vulnerable web applications for pentesting with single command.<br>
This application is docker based so make sure the system supports docker. Docker will be installed automatically on first-run if it isn't found.
## Currently supported Vulnerable Web Applications
- webgoat
- pygoat
- juice-shop
- wrongsecrets
- bwapp

## Quick Start
When running Vulnerable Web Application for the first time
```
./lab <app-name>  
```
To stop a running application
```
./lab <app-name> stop
```
To start an application
```
./lab <app-name> start
```
