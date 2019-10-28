# Variables

Bash allows you to define variables.  You reference their values by
preceding them with a `$`:

```shell
$ j=3
$ echo j
j
$ echo $j
3
```

# Environment variables

Some variables are known to all commands you run and subshells you
spawn.  These are called *environment variables* (in ALL CAPS by
convention).

```
$ export <var>
# This promotes a variable to the environment
```

## PATH -- controls where the system looks for executables

## PS1 -- controls your prompt

All of these can be customized and set when your shell begins by
placing the `export` commands in a file called `.bashrc` in your home
folder.
