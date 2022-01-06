# Using the Terminal

Open up the Terminal. Here are two way to do it.

* Use the app launcher and look for Terminal
* Use spotlight and search for Terminal

Go to the home directory. For me it is `/Users/tony`, but `~` is an alias for that.

```sh
$ cd ~
```

List out all the files and directories in the current directory.

```sh
$ ls
```

Create a directory to put stuff in.

```sh
$ mkdir workspace
```

Go into that directory.

```sh
$ cd workspace
```

See the location of the current directory.

```sh
$ pwd
```

For example:

```sh
$ pwd
/Users/tony/workspace
```

To move back to the parent directory, use `..` which represents the current's directory's parent.

```
$ cd ..
```

For example:

```sh
$ cd ..
$ pwd
/Users/tony
```