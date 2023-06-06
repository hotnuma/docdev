<link href="style.css" rel="stylesheet"></link>

**[ [Home](00-Home.html) | [Xfce](05-Xfce.html) | [DBus](10-DBus.html) | [Bash](15-Bash.html) | Build | [Cpp](25-Cpp.html) | [Gtk](30-Gtk.html) | [Git](35-Git.html) | [Other](99-Other.html) ]**

## Build

---

#### Reference

* Basics
    
    https://wiki.debian.org/BuildingTutorial  


#### Autotools
    
* Install release version
    
    https://stackoverflow.com/questions/4553735/  
    
    `./autogen.sh --enable-debug=no`
    
    or
    
    `./configure --enable-debug=no`
    
    and
    
    `sudo make install-strip`


#### Meson

* Basics
    
    https://mesonbuild.com/IndepthTutorial.html  

* Include a pre-compiled library
    
    https://stackoverflow.com/questions/67925406/  

* Porting projects
    
    [porting-from-autotools](https://mesonbuild.com/Porting-from-autotools.html)  
    [convert-autotools](https://nibblestew.blogspot.com/2016/09/how-to-convert-autotools-project-to.html)  
    [meson-tools](https://github.com/mesonbuild/meson/tree/master/tools)  

* Examples
    
    [viewnior](https://github.com/hellosiyan/Viewnior)  
    [desktop-files-creator](https://github.com/alexkdeveloper/desktop-files-creator)  
    [krishenriksen-pibright](https://github.com/krishenriksen/pibright/blob/master/meson.build)  
    [gsettings-schema](https://discourse.gnome.org/t/installing-gsettings-schema-with-meson/13373)  


#### Dependencies

* Find build dependencies

    https://askubuntu.com/questions/172367/  
    
    ```
    sudo apt-get build-dep --dry-run thunar
    
    apt-cache show thunar

    apt search procps
    ```
    
* pkg-config

    `pkg-config --libs --cflags gtk+-3.0`
    
    Version
    
    `pkg-config --modversion glib-2.0`

* Find program dependencies
    
    https://unix.stackexchange.com/questions/120015/  

* fix library error

    `sudo /sbin/ldconfig -v`


