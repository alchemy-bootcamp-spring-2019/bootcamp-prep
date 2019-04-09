Team File
===

Files are about **content**

# First Recipe

Create a new file in the current directory.

```sh
> pwd
> ls
> touch empty-file.txt
```

Check contents of the file.

```sh
> ls
> cat empty-file.txt
```

 Remove the empty file.
 
```sh
> ls
> rm empty-file.txt
> ls
```

# Second Recipe

Create a new file and place some text into the file.

```sh
> pwd
> ls
> echo "text in a file" > content-file.txt
> ls
> cat content-file.txt  
```

Replace the contents of the file with some new text. 

```sh
> ls
> echo "change text in a file" > content-file.txt
> ls
> cat content-file.txt
```

 Remove the file.

```sh
> ls
> rm content-file.txt
> ls
```
