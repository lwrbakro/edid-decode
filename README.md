# edid-decode
Fork of xorg/fdo edid-decode with patches applied. The "default" branch is the latest rebased and patched branch I've built.

## Requirements
    sudo apt-get install gcc libc6-dev
    
## Install
    make

## Examples
    sudo ./edid-rw 0 | edid-decode
    sudo ./edid-rw 2 | edid-decode
    sudo ./edid-rw 3 | edid-decode

`edid-rw` is from: https://github.com/bulletmark/edid-rw

