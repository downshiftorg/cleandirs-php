# cleandirs

This PHP script is top notch lolz for cleaning out directories that contain numerically
named directories - i.e `10/` `11/` `13/` etc..

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
