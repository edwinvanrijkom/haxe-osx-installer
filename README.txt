Depencies to build the package installer :
XCode 2.4 with Developer tools

- Build haxe from source using install.ml
Make sure you've updated your version to mirror configuration changes.
See : http://haxe.org/compile

- Create the following file structure :
haxe
-------bin
-------haxe
--------------doc
--------------std

- Put all revelants files in them.

- Open haxe.pmproj
Correct the paths depending of your installation.
Verify with vien interface button.
Save.

- Launch from a shell :
$ ./package
The script require adminstrative rights.