# pswd &nbsp; ![DEVELOPMENT STATUS: completed](https://badgen.net/badge/DEVELOPMENT%20STATUS/completed/green)

A simple python script that generates random passwords for you.


## Examples:

### Simple usage:
```console
$ pswd
```

### An 8-char long password with no special characters:
```console
$ pswd -l 8 --no-special
```

### Hide the password output (it'll still be copied to the clipboard):
```console
$ pswd --hide
```

### For more details:
```console
$ pswd --help
```

## How-to:
1. Put the [**pswd**](pswd) script with your other **bin**aries, or in a separate folder, but then don't forget
to include that folder to your **PATH** variable (There are plenty of resources out there if you don't know how to do the latter)
3. Add execution rights to it: ```$ chmod u+x pswd```
4. Rehash to use instantly: ```$ rehash```

## Requirments:
- `python 3.10` or greater
- `pyperclip` module if you want the copying functionality
