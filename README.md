# rmbg

`GhostBG` a.k.a. `rmbg` is just a Bash wrapper and MacOS app for the python `rembg` command line utility.

It does pretty much everything you need to remove the background from images in batches.

## Installation:

```
git clone https://github.com/phx/rmbg
cd rmbg
./rmbg /path/to/image
```

`rmbg` creates an alias in `/usr/local/bin`, so next time you should be able to simply run:

```
rmbg /path/to/image
```

or

```
rmbg /path/to/folder/*
```

## MacOS app:

```
mv GhostBG.app /Applications/
```

## Uninstall:

```
rm -rf ~/.rmbg
rm -rf /Application/GhostBG.app
rm -f /usr/local/bin/rmbg
```
