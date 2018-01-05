Todo
====


Install
-------

```sh
# grab the repo
$ git clone git://github.com/joshbenham/todo ~/.todo

# chmod todo file
$ chmod +x ~/.todo/todo

# copy to bin directory
$ ln -s ~/.todo/todo ~/bin/todo
```


How To Use
----------

Simple todo script (requires clint)

```sh
# if clint is not installed
$ pip install clint

# todo usage
$ todo list
$ todo add <message>
$ todo finish <number>
$ todo delete <number>
```
