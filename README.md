# What is this?
It's a "hello world" example of the go-binary charm layer

# How can I use it?

```
$ mkdir -p /tmp/charms/layers
$ cd /tmp/charms/layers
$ git clone <this-repo>
$ cd simple-server-charm
$ make
$ cd ../../../
$ juju deploy local:trusty/simple-server-charm
```
