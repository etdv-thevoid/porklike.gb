# porklike.gb

A port of the wonderful [Porklike](https://krystman.itch.io/porklike), created
by [Krystian Majewski](https://twitter.com/krystman), to the original Game Boy!
Please see the original pico-8 game at https://krystman.itch.io/porklike for
more information.

See the game's itch.io page here: https://binji.itch.io/porklikegb

## Controls

| Action | Button |
| - | - |
| Move character | D-pad |
| Inventory/Confirm | A button |
| Cancel | B button |

## Building

Porklike.gb uses the GBDK2020 toolkit, RGBGFX, as well as some Python3 scripts.

```sh
$ git clone -b v4.4.0 https://github.com/gbdk-2020/gbdk-2020
$ make -C gbdk-2020
```
```sh
$ git clone -b v0.7.0 https://github.com/rednex/rgbds
$ make -C rgbds
```
```sh
$ make
```

## License

The source of the Gameboy port is copyright Ben Smith, and is MIT licensed. All
game content is owned by the original copyright holders.
