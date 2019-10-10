# Recording your session

Everyone should type the following command *exactly* on the command
line in their home folder (do not type the `$` -- that's just the
prompt):

```shell
$ script -t 10oct19.timing 10oct19.script
```

From this point on, everything you type in this session will recorded
for you to playback, optionally at a variable speed (pausing is,
unfortunately, not possible).

## To end the recording

You will type:
```shell
$ exit
```

## To replay the recording at regular speed

```shell
$ scriptreplay -t 10oct19.timing -s 10oct19.script
```

## To replay the recording at, say, 3.5x speed

```shell
$ scriptreplay -t 10oct19.timing -s 10oct19.script -d 3.5
```

Let's test this out...

# echo

This is a useful command that parrots what you type back to the screen
```shell
$ echo Hello World
Hello World
```


# Taking notes

To add a note while on the command line, preface your note with the
`#` character.  You can do this on the whole line, or after a command
before hitting return.

```shell
$ #This is a commment, whole line is ignored
$ echo Hello #Everything from here on is ignored
Hello
$ # Output remained
```
