Parse server
=====================

A Parse server instance. Has configurations for projects:
- Mesto
 

## Build Setup

First, you should install MongoDB (if you haven't it yet):
``` bash
brew install mongodb
```

Before running server, you should start MongoDB daemon:
``` bash
mongod --dbpath <path to data directory>
```
 
Next, choose you project and run appropriate npm-script:
``` bash
# for Mesto project
npm run mesto
```
The server will listen 5000 port.
