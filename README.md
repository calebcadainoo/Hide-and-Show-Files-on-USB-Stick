# Hide-and-Show-Files-on-USB-Stick
A simple trick to hide and show content of your USB stick

### To Hide The Files on USB
1. Create a text file eg. ``hide.txt`` in the USB drive eg. ``I:/``
2. Paste the following code in the file
```sh
attrib +s +h /s /d *
```
3. Change the file extension from ``.txt`` to ``.bat``. Hence ``hide.txt`` becomes ``hide.bat``
4. Double-click to run it


### To Show The Files on USB
1. Repeat the steps above but paste the following code instead
```sh
attrib -s -h /s /d *
```

