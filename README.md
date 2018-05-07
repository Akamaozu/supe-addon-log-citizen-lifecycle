# [Supe](https://github.com/Akamaozu/node-supe) Add-On: Log Citizen Lifecycle

## Log citizen start-up, shutdown, crashes and overcrashes.
![npm version](http://public.designbymobi.us/img/node-satellite-lifecycle.png)

# Install

```
npm install --save supe-addon-log-citizen-lifecycle
```

# Usage

```
var supervisor = require('supe')(),
    log_citizen_lifecycle_addon = require('supe-addon-log-citizen-lifecycle');

supervisor.use( log_citizen_lifecycle_addon );
```