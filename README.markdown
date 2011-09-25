INSTALL
-------
sudo ./install

This command copies the picker, g++, and gcc files into /usr/bin with all access rights enabled.

Setting version to use
----------------------
Create a file called `.gvm`.  In this file place the paths to the correct tools to use for your project.

    /usr/bin/gcc-4.4
    /usr/bin/g++-4.4

From this point forward all calls to gcc and g++ in this directory or any subdirectory will use these executables instead.

It is also possible to nest these (although i don't see a reason).  The first `.gvm` file found that contains an override will be used.
