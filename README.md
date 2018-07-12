# ChatApp-MongoDB-Socket.io

Just a practising project to know how **Socket.io** works and know its capability.

It is going to use **MongoDB** to store the content we chat during a chat.

# Guide

If you want to build this project. **You need to install MongoDB first!**

After you install it. You have to set it up.

You can use either a config file called mongod.conf

```sh
$ mongod --config /etc/mongod.conf
```

or run command with some options, like

```sh
$ mongod --dbpath /usr/local/mongodb-data
```

```sh
$ mongod --port 8000
```

[Offical documentation here](https://docs.mongodb.com/manual/reference/configuration-options/)

### Start mongod as a Daemon

To run a mongod process as a daemon (i.e. fork), and write its output to a log file, use the --fork and --logpath options. You must create the log directory; however, mongod will create the log file if it does not exist.

The following command starts mongod as a daemon and records log output to /var/log/mongodb.log.

```sh
$ mongod --fork --logpath /var/log/mongodb.log
```
Then

```sh
$ npm install
```

```sh
$ npm run start
```

Enjoy it!
