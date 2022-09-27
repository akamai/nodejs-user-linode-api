nodejs-user-linode-api
======================

### About

Source for a docker container for a node-red based API for 

repo is synced with docker hub at brianapley/nodejs-user-linode-api.



## Launching via docker hub (example)

```
docker run -it -p 1880:1880 -v nrdata:/data --name nodejs brianapley/nodejs-user-linode-api
```

Once launched, UI can be accessed via http://host:1880/.

