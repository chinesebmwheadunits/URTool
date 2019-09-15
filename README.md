# URTool
URTool Extract and Repack android images from 5-8.1 and 9 (BIN,IMG,DAT-BR) Under Windows environment

This Fork of URTool is for unpacking the OEM Folder of Chinese BMW Android 8.1.0/9.0 OTA Update files for further editing !


# Usage
```
For Android 8.1 and Android 9.0 on PX6:

Rename your Android 8.1.0 OTA file to PX6.zip , then put it into main file directory where the unpack_system_android8.bat is
start unpack_oem_android8.bat
When successfully finished a "oem" folder is created with all the files.

For Android 9.0 on Snapdragon:
Rename your Android 9.0 OTA file to android9.zip , then put it into main file directory where the unpack_system_android9.bat is
start unpack_system_android9.bat
When successfully finished a "system_android9" folder is created with all the files.

# Functions
```

unpack_oem_android8.bat function:
Unpacks oem.new.bat.br file automatically.

unpack_system_android9.bat function: 
Unpacks system.new.bat.br file automatically.

URtool.bat function:

Unpack vendor.img/.dat.br, system.img/.dat.br, payload.bin automatically.
Repack vendor.img/.dat.br, system.img/.dat.br,  exception for payload.bin but this tool deliver to you system.img ext4 for flashing purposes.
URTool deliver to you original system permissions and symlinks
```


# Credits
```
See credits.txt for binary authors
```

# Tests
```
*Not working on android 9 roms yet, make_ext4fs binary is not present in Pie repository*
```


