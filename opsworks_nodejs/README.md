## OpsWorks Node.js Cookbook Override


Opsworks_nodejs expects there to be a file named `server.js` at the root of the nodejs application.


This override effectively removes the `.js` from the path, allowing you to run the application from  a directory named `server` instead.


```
  i.e, In place of monitoring `node server.js` in the monit script, it will use `node server` instead.
```