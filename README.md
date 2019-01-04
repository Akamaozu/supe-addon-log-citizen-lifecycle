# [Supe](https://github.com/Akamaozu/node-supe) Add-On: Log Citizen Lifecycle

## Log citizen start-up, shutdown, crashes and overcrashes.
![npm version](http://public.designbymobi.us/img/node-satellite-lifecycle.png)

# NOTE: Irrelevant for Supe versions 0.4.0 and above
This behavior was rolled into Supe core at [version 0.4.0](https://github.com/Akamaozu/node-supe/pull/14/files#diff-02cd71546d8ca715b696f3d48e122bc0).

# Install

```
npm install --save supe-addon-log-citizen-lifecycle
```

# Usage

```
var supervisor = require('supe')(),
    log_citizen_lifecycle_addon = require('supe-addon-log-citizen-lifecycle');

supervisor.use( log_citizen_lifecycle_addon );
