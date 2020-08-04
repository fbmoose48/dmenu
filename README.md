# Custom build of dmenu

## patches

+ dmenu-border-4.9
+ dmenu-fuzzymatch-4.9
+ dmenu-highpriority-4.9
+ dmenu-lineheight-4.9
+ dmenu-mousesupport-4.9
+ dmenu-xresources-4.9

## Installation

```
git clone https://github.com/fbmooose48/dmenu
cd dmenu
sudo make install
```

`make` is required to build.
`fontconfig` is required for the default build, since it asks `fontconfig` for your system monospace font.  
`libX11` and `libXft` are required as well.
