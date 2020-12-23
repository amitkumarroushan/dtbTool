# dtbTool

Use :  For Generating `dt.img` from `xxx.dtb`

Credits : Original Code can be found <a href="https://github.com/AndroiableDroid/dtbTool">here</a>


# Setting Up
1. `sudo apt-get install device-tree-compiler`
2. `make`


# Generating dt.img

-s = defines pagesize (usually RAM in MB ; here I have 2GB) <br>
-o = output name

`./dtbTool -s 2048 -o dt.img ~/path/to/dtb/`



