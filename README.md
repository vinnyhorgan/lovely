# Lovely

Lovely allows you to start building your application immediatly providing a minimalistic template using the language Moonscript and the Love engine.

## Dependencies

To use lovely a few dependencies are required:

- [Love2d](https://love2d.org)
- [Moonscript compiler](https://moonscript.org) (install it with [LuaRocks](https://luarocks.org) using the command )
- [Love-release](https://github.com/MisterDA/love-release)
- Python 2 (most linux distros should have this preinstalled)

To get Moonscript and Love-release you have to use [LuaRocks](https://luarocks.org), the Lua package manager. Once installed use these two commands:

- ```luarocks install https://luarocks.org/manifests/leafo/moonscript-dev-1.rockspec```
- ```luarocks install love-release``` (love-release also depends on the libzip-dev package you can install with every package manager)

## Setup

The only thing to do for setup is changing the path to the lua executable in the run script, it will presume it's in your path by default. To run the scripts you should also change the permissions with this command ```chmod 777 run package```.

## Features

- Script to compile and run the project
- Integration with web debugger [lovebird](https://github.com/rxi/lovebird)
- Script to package the project for every platform (remember to remove lovebird before running)

If you happen to use the [micro](https://micro-editor.github.io/) editor, i wrote a Moonscript [syntax-file](https://github.com/vinnyhorgan/Moonscript-Syntax-Micro) for it.