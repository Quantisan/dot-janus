my [janus](https://github.com/carlhuda/janus) setup for vim. Mostly for working with Clojure.

## Setup

```bash
git submodule init
git submodule update
ln -s ~/.janus/vimrc.before ~/.vimrc.before
ln -s ~/.janus/vimrc.after ~/.vimrc.after
```

## Optional Steps

### A few plugins make use of shell programs. These need to be installed for the respective plugins to work.

* [Git](http://git-scm.com/)
* [Ack](http://betterthangrep.com/install/)