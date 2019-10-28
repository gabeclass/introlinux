# Navigating the filesystem

```
whoami                         # who you are
pwd                            # print working directory
cd                             # used to change directory
who                            # show all users logged on
```

# Absolute and relative pathnames

* Every folder on the system has an absolute "address" called its
  *absolute pathname*, beginning with the root directory `/` and
  descending through the file tree.  So, for instance, my home
  directory on Adroit has absolute pathname `/home/perezgiz`.

* If you enter a folder name that *does not* begin with `/`, the shell
  interprets that as a *relative pathname* (relative to where you are
  right now). In other words, the shell *prepends* the result of `$
  pwd` to what you've typed.

* The above also applies to *filenames*, not just to folder names.

* Shortcuts to refer to certain folders:
  ```
  .                              # where you are right now
  ..                             # the folder one level above you
  ~                              # *your* home folder (/home/<youruserID>)
  ~<user>                        # home folder of <user>
  ```

# Getting information or help

```
man <command>                  # displays the manual page for <command>

```

It's important to understand the general *anatomy* of a command. The
top of a `man` page explains it for any given command.

What if you can't find the `man` page?

```
apropos <string>               # lists man pages potential pertinent to <string>
```


# `less` -- a pagination program
```
less <file>                    # paginate thru file
```

`man` is really displayed with `less`

