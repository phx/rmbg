![GhostBG](./icon.png?raw=true)

# GhostBG

`GhostBG` a.k.a. `rmbg` is just a Bash wrapper and MacOS app for the Python3 [`rembg`](https://pypi.org/project/rembg/) command line utility.

It does pretty much everything you need to remove the background from images in batches.

(installs all dependencies and runs in a virtualenv inside `~/.rmbg`)

`rmbg` is also cross-compatible with all versions of Linux.

**External dependencies:**

- `bash`
- `python3`
- `curl` (if `pip` is not installed)

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

You can double-click GhostBG from your Applications, or drag it to your dock and click it.

It will open a Finder prompt for you to select the images you wish to edit.

You can also use it as a droplet by simply selecting the images from Finder and dragging them onto the GhostBG icon to start processing them immediately.

## Uninstall:

```
rm -rf ~/.rmbg
rm -rf /Application/GhostBG.app
rm -f /usr/local/bin/rmbg
```
