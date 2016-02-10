#bin

**bin** is a collection of scripts and utilities that live in my Dropbox and are added to my path. At some point in time, each of these scripts seemed like a useful (or fun) thing to have.

By Chris Beard (https://github.com/chrisbeard).


## Dependencies
TODO


##Contents

#### age
A reminder of how one has lived.
```
$ age
Time since XX:XX AM/PM, Month Day Year:
           xx years
        x,xxx weeks
        x,xxx days
      xxx,xxx hours
   xx,xxx,xxx minutes
  xxx,xxx,xxx seconds
$
```

####compressibility
Shows how much space can be saved by compressing a *file* (does not work for directories).
```
$ compressibility log.txt
file size 22174
gzip size 3947 (17%)
bz2 size  4573 (20%)
$
```

####sizeof
Shows the size of files and/or directories.
```
$ sizeof *.txt *.zip
147 bytes	groceries.txt
678 bytes	things to bring.txt
12 MB	backup.zip
$
```
