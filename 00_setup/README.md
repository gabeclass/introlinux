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
