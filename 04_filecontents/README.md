# Working with file contents

## `nano` -- a basic text editor

To open a file with `nano`, type:
```shell
$ nano <filename>
```

Editing commands follow in there.  Let's explore...

## Remember `less` (the paginator program)
```
less <file>                    # paginate thru file
```

## Other file content utilities

```
cat file1 file2 file3          # display contents of file1, file2, file3 in order
tac file1 file2 file3          # like cat, with each file (reversed)
head <file>                    # show top few lines of <file>
tail <file>                    # show last few lines of <file>
```

Let's add some file content and play with the flags/options to `head`
and `tail`...

## Poor man's text editor

To be explained later, but type:
```shell
$ cat >> poorman.txt
This is a quick way
to make a silly file
with a few notes.
<Ctrl-d>
```

Now examine the contents of `poorman.txt` (with `less`, or `cat`, or
`head`, etc).  The `>>` appends.  To overwrite, do the same with `>`.
