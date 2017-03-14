# Roku Remote

A remote to control a roku on your local network.

## Usage

To use this, find the ip address of your roku, and change line 104

```javascript
var rokuAddress = "http://192.168.1.24:8060/";
```
to 
```javascript
var rokuAddress = "http://[your.rokus.ip]:8060/";
```
