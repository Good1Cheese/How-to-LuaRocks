# How-to-LuaRocks

## Guide to Installing LuaRocks package manager for Lua

1) Download .exe files of ***Lua***.<br>
Put it in any folder, and add this folder to ***PATH***.

2) Download ***MSYS2***.<br>
After installing, enter command: `pacman -S --needed base-devel mingw-w64-x86_64-toolchain`.<br>
Then Install all packages.<br>
Add `*path_to_MSYS2\bin*` folder to ***PATH***.

3) Download ***CMake***.<br>
Add this folder to PATH environment variables.<br>
Add `*path_to_CMake\bin*` folder to ***PATH***.

4) Download ***Luarocks***.<br>
Add Luarocks folder to ***PATH***.

5) Create ***include*** folder in ***Luarocks*** directory<br>
Download ***Lua*** source files, and paste it in ***include*** folder

6) Create ***lib*** folder in ***Luarocks*** directory.<br>
Copy in it lua ***.dll*** file.

7) **Setup Luarocks:**. <br>
`LUA_INCDIR = path to folder ***include***`<br>
`LUA_LIBDIR = path to folder ***lib***`<br>
other lua directories = path to ***Lua*** folder.

## P.S.
This guide is written for people like myself who just want LuaRocks to work.<br>
I am only an amateur; you may know about this topic better than me.

## Links
[Explanation of Enviroment variables](https://www.java.com/en/download/help/path.html) <br>
[LuaRocks config description](https://github.com/luarocks/luarocks/wiki/Config-file-format) <br>
[Installing MSYS2 with MinGW](https://code.visualstudio.com/docs/cpp/config-mingw)
