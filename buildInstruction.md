## Build Instruction
for those who want to build this project please follow the instruction provided below

### F5 method
for quick and easy testing use the F5 key to start the visual studio extension developement mode
this will open up a new VSCode window in Extension developement mode (otherwise know as extension developement host).

### other method
if you want to build the project to test thru a clean or use it with modification you may do so by following this instruction

Make sure you have node.js installed

on your Visual Studio terminal type in this command (without quote)

`npm install -g vsce`

after installing you can build the project thru this command

`vsce package`

this will create a package vsix file on the root folder of the project.
afterward you may install it to your version of visual studio code following the
manual instruction.

### support
while I offer support for this extension, please take note that I DON'T offer support for using vsce as this
is provided by microsoft for extension developement and publishing convience. please contact the visual studio code community for assistance.