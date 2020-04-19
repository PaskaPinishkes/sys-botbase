# sys-botbase fork based on olliz0r sys-botbase based on jakibakis sys-netcheat
The purpose of this sys-module is to allow users to use controllers on their computers and mirror them to the Switch allowing services such as Parsec or Steam Remote-Play Together to be usable on the Switch. Everything unrelated to button input has been removed to save memory.

## Warning:
If anything goes wrong, it's not my fault, so don't blame me. This sys-module has been tested.

Copy the sys-botbase.nsp file to sdmc://atmosphere/contents/4300000000000074 and rename it to exefs.nsp.
Create a new folder in sdmc://atmosphere/contents/4300000000000074 names "flags".
Create a empty file called boot2.flag inside this folder.
Restart your switch.

The sysmodule opens a socket connection on port 6000.
