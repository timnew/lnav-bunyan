lnav-bunyan
============

> [lnav] is powerful yet easy-to-use log browser.
> `lnav-bunyan` is group of [bunyan] log format declarations for [lnav]

## Install

Install `lnav`
```shell
$ brew install lnav
```

Install `lnav-bunyan`
```shell
$ lnav -i https://github.com/timnew/lnav-bunyan.git
```
Then the repo will be cloned into `~/.lnav/formats`

## Update

Update `lnav-bunyan`
```shell
$ lnav -u
```
All latest modification on the github will be pulled

## How to use

Well, these is no special trick to use `lnav` with `lnav-bunyan`

Suppose all log files are located in `./logs`

```shell
$ lnav ./logs
```

Once you open the log, you can `filter` or even execute `SQL` query on your logs

For more detail about lnav tricks, check out [lnav document]

[lnav]: http://lnav.org/
[bunyan]: https://github.com/trentm/node-bunyan
[lnav document]: http://lnav.readthedocs.org/en/latest/
