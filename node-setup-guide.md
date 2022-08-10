# Node Setup Guide

Follow the getting started and building steps from the [official Bamboo repository](https://github.com/bamboo-crypto/bamboo/blob/master/README.md#getting-started).

Build the node with `make server`.

In your `bamboo/` directory make a new folder called `data`. 

Now you can run the node with `./bin/server`.

## Ports

The standard port is 3000.

## Launch Parameters

`-ip <ip>` -set custom ip

`-n <name>` -set custom name

`-p <port>` -set custom port

`--testnet` -enable testnet

`--disable-limiter` -disable rate-limiting

`--firewall` -use if the nodes port is not forwarded
