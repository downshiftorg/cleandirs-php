# cleandirs

This PHP script is top notch lolz for cleaning out directories. Directories are sorted
by creation time - oldest directories deleted first.

## Setup

```
$ sudo mv cleandirs /usr/local/bin
$ sudo chmod +x /usr/local/bin/cleandirs
```

## Usage

```
$ sudo cleandirs /var/www/builds
```

The `KEEP_DIRS` constant in the script will say how many directories should be kept.
The most recent directories according to the number of the directory will be kept.
