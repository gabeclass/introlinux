# Recording your session


## Starting the recording

Everyone should type the following command *exactly* on the command
line in their home folder (do not type the `$` -- that's just the
prompt):

```shell
$ script -timing=dryrun.timing dryrun.script
```

From this point on, everything you type in this session will recorded.
Let's test this out...

## echo

This is a useful command that parrots what you type back to the screen
```shell
$ echo Hello World
Hello World
```


## Taking notes / comments in bash

To add a note while on the command line, preface your note with the
`#` character.  You can do this on the whole line, or after a command
before hitting return.

```shell
$ #This is a commment, whole line is ignored
$ echo Hello #Everything from here on is ignored
Hello
$ # Output remained
```


## Ending the recording

You will type:
```shell
$ exit
```
Alternately, press `Ctrl-d`.


## To replay the recording

You can now either:
* play back the session with realistic timing, optionally sped up or
slowed down (pausing is, unfortunately, not possible); or
* dump the contents of your session all at once to the screen




### at regular speed

```shell
$ scriptreplay -t dryrun.timing -s dryrun.script
```

### at, say, 3.5x speed

```shell
$ scriptreplay -t dryrun.timing -s dryrun.script -d 3.5
```


## Recommendations

* Make a new script for each "module" we go through today, so you can
  review your work more atomically.

* **ASK QUESTIONS!** If something goes wrong, check whether you typed
  something wrong (you probably did). But then... speak up!  I may
  have to move on and not be able to address it, but ask anyway.
  
## Helpful hints

* Up/down arrow let you navigate through your recent command history
  quickly.
  
* The `TAB` key can provide helpful autocompletion

* Other key-navigation shortcuts that we can't focus on today but
  which help actualize your will on the command line with less
  latency.  Some examples (`M` denotes "meta" or "Alt" key -- Mac
  users need to enable "option as meta" in Terminal --> Preferences
  --> Keyboard (I think?)
  
  ```
  C-a                            # Move cursor to start of line
  C-e                            # Move cursor to end of line
  C-d                            # Delete forward one character
  M-d                            # Delete forward one "word"
  M-backspace                    # Delete backward one "word"
  M-f                            # Move cursor forward one "word"
  M-b                            # Move cursor backward one "word"
  
  C-u                            # Delete from cursor to start of line
  C-k                            # Delete from cursor to end of line
  C-y                            # "Yank" (pasted) last thing deleted
  ```


## The importance of practice... and of playing "golf"

The only way to get better at the command line (or any skill) is to
use it *regularly*.  Challenge yourself to do more mouse-free.

Also challenge yourself to do things in as few key-presses as possible
(like fewer strokes in golf). The command line can become quite
onerous if you have to type too much.  Train your fingers to make the
computer type as much as possible for you.
