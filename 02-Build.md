**[ [Home](00-Home.html) | [Bash](01-Bash.html) | [Build](02-Build.html) | [Cpp](03-Cpp.html) | [Git](04-Git.html) | [Gtk](05-Gtk.html) | [Linux](06-Linux.html) | [Src](07-Src.html) ]**

#### Dependencies

[The X Window system](https://tronche.com/gui/x/)

[BuildingTutorial](https://wiki.debian.org/BuildingTutorial)

[Find build deps](https://askubuntu.com/questions/172367/how-do-i-find-the-dependencies-when-building-software-from-source)

* Find build dependencies
    ```
    apt search procps
    ```
    ```
    sudo apt-get build-dep --dry-run thunar
    ```
* ldd
    
    fix deps
    
    https://unix.stackexchange.com/questions/120015/

* fix library error

    sudo /sbin/ldconfig -v

* pkg-config

    pkg-config --libs --cflags gtk+-3.0
    pkg-config --modversion glib-2.0

#### Meson

[Include a pre-compiled library](https://stackoverflow.com/questions/67925406/)

[Porting from Autotools](https://mesonbuild.com/Porting-from-autotools.html)

[Autotools to Meson](https://nibblestew.blogspot.com/2016/09/how-to-convert-autotools-project-to.html)

[Meson In-depth Tutorial](https://mesonbuild.com/IndepthTutorial.html)

[meson/ac_converter.py](https://github.com/mesonbuild/meson/blob/master/tools/ac_converter.py)

[meson/cmake2meson.py](https://github.com/mesonbuild/meson/blob/master/tools/cmake2meson.py)
