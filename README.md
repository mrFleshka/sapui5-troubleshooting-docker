# Info

SAPUI5 Troubleshooting practice (For SAPUI5 version: 1.65.1).

[Documentation](https://sapui5.hana.ondemand.com/#/topic/5661952e72df471b932eddc10350c081)

Used with docker (nginx proxy-pass + node server).
 
# Run

For start add network in docker (used for custom windows network with routing to virtual machine):

```bash
docker network add develope
```

Then just start docker:

```bash
docker-compose up
```

Demo site available at [troubleshooting.sapui5.test](http://troubleshooting.sapui5.test/index.html)