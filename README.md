# aurix_openocd_gdb_example
Allready builded openocd and gdb client for windows from tricore-oss repos and example of debuging in vscode

# Openocd
https://github.com/tricore-oss/openocd

# GDB
https://github.com/tricore-oss/binutils-gdb

# Example
There will be an cmake based blink example soon, but now in example folder placed my vscode config files as is for debuging Blinky_LED_1_KIT_TC277_TFT from https://github.com/Infineon/AURIX_code_examples builded by Aurix Studio. You should rewrite all hardcoded paths to unziped tools from zip archives from this repo.
Before starting openocd debug you need to launch tas server. Typically located at C:\Program Files\DAS64\servers\tas_server.exe
