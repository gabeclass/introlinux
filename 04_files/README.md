# Working with files

## Poor man's empty file creator

```
touch <name>                   # make an empty file called <name>
```

But not *really* what `touch` does...

## Linux is case-sensitive!

```shell
$ touch MyFile # This is not the same as...
$ touch myfile # ...this other thing.
```

## Other file-related commands
```
rm                             # remove the file
rm -r <dir>                    # remove a nonempty directory and its contents
cp file1 file2                 # create a copy of file1 named file2 (can use paths)
cp -r <path/dir> .             # copy <path/dir> to the current directory
mv <path/name> <path2/name2>   # move <path/name> to <path2/name2>
mv <path/name> <path2/name2>   # rename <path/name> to <path2/name2>
```
