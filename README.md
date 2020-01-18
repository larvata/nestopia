## Whats New
1. Added a window position remember feature for SDL.

## Building (macOS only)

#### Install Dependencies

```
brew install autoconf automake autoconf-archive pkg-config libarchive libepoxy
```

#### Compile 
```
export PKG_CONFIG_PATH=/usr/local/opt/libarchive/lib/pkgconfig/
autoreconf -vif
./configure --disable-gui

make
```
Optionally:
```
make install
```

## About
This project is forked from:
https://github.com/0ldsk00l/nestopia
