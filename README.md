# Lite XL Net Plugin

This repository provides a **native** binding to
[SDL2_net](https://github.com/libsdl-org/SDL_net) to provide TCP and UDP
sockets support in Lite XL. Inspiration was taken from luasdl2
[sdl-net](https://github.com/Tangent128/luasdl2/tree/master/sdl-net) wrapper.

## Building

You will need to have meson and a working build environment for your operating
system. Then, to build just execute the following commands:

```sh
meson setup build
meson compile -C build
```

## Installation

To install just copy the generated library file to your libraries directory:

```sh
cp build/net.so ~/.config/lite-xl/libraries/
```

## Usage:

You can view the API documention on the [docs](docs/net.lua) subdirectory,
and also consult official [SDL2_net](https://github.com/libsdl-org/SDL_net)
header file which has useful doc comments.
