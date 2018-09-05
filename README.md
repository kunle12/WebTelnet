# WebTelnet: a web-based telnet client using websocket

## Introduction
This code is a 'cleaned up' version of telnet client derived from [VTX_ClientServer](https://github.com/codewar65/VTX_ClientServer). The changes are minimal and the client is preconfigured to connect to a local PyRIDE system with the support of [websockify](https://github.com/novnc/websockify). Credits all go to [codewar65](https://github.com/codewar65).

## Setup
* Ensure the backend telnet service is running (assuming a PyRIDE system is running).
* Install and run up websockify.

```
pip install websockify
websockify -D 7003 localhost 27005
```
* Point a browser to ```index.html``` under WebTelnet directory.
