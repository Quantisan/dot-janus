my [janus](https://github.com/carlhuda/janus) setup for vim. Mostly for working with Clojure.

## Setup

```bash
git submodule init
git submodule update
ln -s ~/.janus/vimrc.before ~/.vimrc.before
ln -s ~/.janus/vimrc.after ~/.vimrc.after
```

### Install [lein-tarsier plugin](https://github.com/sattvik/lein-tarsier).

## Optional Steps

### A few plugins make use of shell programs. These need to be installed for the respective plugins to work.

* [Git](http://git-scm.com/)
* [Ack](http://betterthangrep.com/install/)

### A script to start nailgun in an empty port to enable multiple REPLs

Symlink `vc` and `unused-port` into your `bin`. For example, if `~/bin` is in your path:

```bash
ln -s ~/.janus/vc ~/bin/vc
ln -s ~/.janus/unused-port ~/bin/unused-port
```
