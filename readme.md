## Give it access to storage
(see https://wiki.termux.com/wiki/Internal_and_external_storage)
```
termux-setup-storage
```

## Install packages
```
pkg install bc exiftool imagemagick termux-file-editor
```
`termux-file-editor` allows one to share single files to termux, which will result in the file being copied in `~/download` folder and then have its full path passed to `~bin/termux-file-editor`, which I then use to interactively add a title (in the XMP metadata) and optionally recompress the jpg.
