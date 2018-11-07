# bash-utils
bash utility scripts


## timeout

### Usage

```
./timeout 2 ping www.google.com
```

First argument specifies timeout in seconds.
Will execute command given by subsequent arguments, e.g.

```
ping www.google.com
```

and kills it (and exits with code 1) after specified delay if it hasn't
exited yet.

### Install


To install into current directory (e.g. on Travis)
```
curl -O https://raw.githubusercontent.com/FieldServer/bash-utils/master/timeout && chmod +x ./timeout
```
