# Realtime Raytracing

An experiment with C++, SDL2 and OpenMP-based realtime raytracing on the CPU.

* Move a sphere using either the arrow keys or `w`, `a`, `s`, `d`.
* Switch to the next sphere with `space` or `tab`.
* Toggle fullscreen with `f` or `f11`.
* Quit with `q` or `esc`.
* You can also move the current sphere with a joystick, then press a key to select the next one.

## Requirements

* SDL2 (`sdl2` and optionally `sdl2_image`, `sdl2_mixer`, `sdl2_ttf`, `sdl2_net` and `sdl2_sound`)
* OpenMP (`libomp`)
* CMake (`cmake`)
* GNU Make (`make`)

## Screenshot

![screenshot](img/screenshot.png)

## Building

    make

## Running

    make run

Tested on Arch Linux and macOS.

The spheres can be moved around with a joystick / joypad.

Written with the [Orbiton](https://github.com/xyproto/orbiton) editor.

## General info

* Version: 0.1.0
* Author: Alexander F. Rødseth &lt;xyproto@archlinux.org&gt;
* License: MIT
