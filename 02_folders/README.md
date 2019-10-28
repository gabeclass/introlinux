# Working with folders

```
ls                             # list directory contents (plus other uses)
mkdir <path/name>              # make directory
rmdir <path/name>              # remove directory (if empty)
```

What if I want to create, in my home folder, a bunch of nested
directories like `bootcamp/monday/introlinux/03folders`?

* Do I have to be *in* a directory `dirA` to create another directory
  `dirB` inside `dirA`?
  
* What's the golfiest way to make the nested tree
  `bootcamp/monday/introlinux/03folders`?  *HINT:* read the `man`
  page!
  
* **Challenge:** now, given everything that's gone on so far, delete
  all those directories in as few keystrokes as you can (ABG!)
	

## BONUS -- a taxonomy of commands

```
type <command>                 # what kind of 'verb' is <command>
```

The four categories of "verbs" in `bash`:
1. Aliases
2. Shell functions (`bash` is a full-featured programming language;
   abeyond our scope today)
3. Shell builtins
4. Files (more precisely, executable files -- how does `bash` know
   where those files live?  More on this later...
