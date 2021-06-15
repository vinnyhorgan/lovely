# Lovely

Lovely allows you to start building your application immediatly providing a minimalistic template using the language Moonscript and the Love engine.

## Dependencies

To use lovely a few dependencies are required:

- [Love2d](https://love2d.org)
- [Moonscript compiler](https://moonscript.org)
- [Love-release](https://github.com/MisterDA/love-release)

To get Moonscript and love-release you have to use [LuaRocks](https://luarocks.org), the Lua package manager. Once installed use these two commands:

- ```luarocks install https://luarocks.org/manifests/leafo/moonscript-dev-1.rockspec```
- ```luarocks install love-release``` (love-release also depends on the libzip-dev package you can install with every package manager)

## Setup

The only thing to do for setup is changing the path to the lua executable in the run script, it will presume it's in your path by default. To run the scripts you should also change the permissions with this command ```chmod 777 run package particle-editor```.

## Features

- Moonscript language support
- Particle editor to make better effects
- Easily distribute your game thanks to love-release
- Most common and useful Love2d libraries provided:

- [g3d](https://github.com/groverburger/g3d) for 3d support
- [splashy](https://github.com/videah/splashy) to display splash screens before the game starts
- [simple tiled implementation](https://github.com/karai17/Simple-Tiled-Implementation) to add support for maps made in the [Tiled](https://www.mapeditor.org/) editor
- [windfield](https://github.com/a327ex/windfield) for collision detection and simple physics
- [anim8](https://github.com/kikito/anim8) for easier animation
- [gamera](https://github.com/kikito/gamera) for easier camera manipulation
- [boipushy](https://github.com/a327ex/boipushy) for controller support
- [lovebird](https://github.com/rxi/lovebird) for web browser debugging capabilities
- [push](https://github.com/Ulydev/push) for resolution handling
- [sock](https://github.com/camchenry/sock.lua) for networking support

If you happen to use the [micro](https://micro-editor.github.io/) editor, i wrote a Moonscript [syntax-file](https://github.com/vinnyhorgan/Moonscript-Syntax-Micro) for it.
