bookmark_dir Gem (bd command)
====

Bookmark Dir (bd command) is a cd-like utility that can bookmark any directory.


How to install
----

Under construction...

```
$ gem install bookmark_dir
```


How to use
----

```
$ bd                     -- show bookmarks (or help if there is no bookmarks)
$ bd -h                  -- show this help
$ bd <name>              -- move to the bookmarked directory
$ bd -a <name>           -- add a bookmark (current directory)
$ bd -a <name> <dir>     -- add a bookmark (specified directory)
$ bd -d                  -- delete a bookmark (select from list)
$ bd -d <name>           -- delete a bookmark (specified bookmark)
$ bd -c                  -- clear all bookmarks
$ bd -m <name1> <name2>  -- rename a bookmark
```

If the specified name is already existing in the bookmarks, the old entry will be replaced with the new one.


Files in config directory
----

A config directory (`~/.bd`) will be automatically created when you use the `bd` command for the first time.

#### ~/.bd/bookmarks

```
dir1    /home/maku/path/to/dir1
```

