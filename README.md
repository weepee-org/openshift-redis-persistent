# redis

Template for running a redis persistent container.

# Installation (easy!)

You need oc (cli tool) locally installed

```sh
> oc new-app https://github.com/ure/openshift-redis-presistent.git --name=redis
```

# Scaling

Create additional redis services with another naming scheme like

```sh
> oc new-app https://github.com/ure/openshift-redis-presistent.git --name=redis0
> oc new-app https://github.com/ure/openshift-redis-presistent.git --name=redis1
```
