# (/・・)ノ kauw window manager
kauw is an expiremental tiling window manager built for x11 using nim

currently it is but a skeleton of what's to come

## goals (・・；)
i have a few goals in mind while writing this project
- written and configured fully in [nim]
- easily configurable
- easily hackable
- be small and fairly minimalist
- help myself learn nim and get around x11

## config
the default config is [src/config.def.nim]; you can duplicate it (and be sure to rename it to config.nim) and make changes to your liking

## development
clone using
```
$ git clone https://github.com/fox-cat/kauw
$ cd kauw
```
build using
```
$ nimble build
```
and you can test using [xephyr]
```
$ Xephyr -ac -screen 1980x1080 -br -reset -terminate 2> /dev/null :2 &
$ DISPLAY=:1 ./kauw
```

## TODO
see [TODO]

[nim]: https://nim-lang.org/
[xephyr]: https://wiki.archlinux.org/index.php/Xephyr
[TODO]: TODO