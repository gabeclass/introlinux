# Bash is a language

Bash has some convenient shorthands that can be leveraged to great
effect.

## Globbing -- matches *filenames* or *folders* only

```
*       # Zero or more characters
?       # Exactly one character
[abc]   # Exactly one of a,b,c
```

This can be combined with `ls` to simplify life considerably...


## Brace expansion -- good for iterating like a `for` loop

```shell
$ echo b{a,e,i,o,u}d
bad bed bid bod bud
```

### Braces also know basic sequences (really ASCII + counting)

```shell
$ echo file{05..21}
# What happens?
```

