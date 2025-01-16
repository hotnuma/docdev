<link href="style.css" rel="stylesheet"></link>

**[ [Home](00-Home.html) | Build | [Git](10-Git.html) | [Bash](15-Bash.html) | [Cpp](25-Cpp.html) | [Gtk](30-Gtk.html) | [Other](99-Other.html) ]**

## Build

---

#### References

https://wiki.debian.org/BuildingTutorial  


#### Autotools
    
* Install release version
    
    https://stackoverflow.com/questions/4553735/  
    
    `./autogen.sh --prefix=/usr/local --enable-debug=no`
    
    or
    
    `./configure --prefix=/usr/local --enable-debug=no`
    
    and
    
    `make -j 4`
    
    `sudo make install-strip`


#### Meson

* Basics
    
    https://mesonbuild.com/IndepthTutorial.html  
    https://mesonbuild.com/Fs-module.html  

* Include a pre-compiled library
    
    https://stackoverflow.com/questions/67925406/  

* Resolve home directory
    
    https://github.com/mesonbuild/meson/issues/6318  

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
    
    Sources depends : `apt-cache showsrc xfwm4 | grep '^Build-Depends'`
    
    Build depends : `apt build-dep --dry-run xfwm4`
    
    Search package : `apt search xfwm4`
    
* pkg-config

    `pkg-config --cflags --libs gtk+-3.0`
    
    Version : `pkg-config --modversion glib-2.0`

* Find program dependencies
    
    https://unix.stackexchange.com/questions/120015/  

* fix library error

    `sudo /sbin/ldconfig -v`


#### Common Dev Packages

* Packages Names

    | PkgConfig               | Package Name            |
    | :---------------------- | :---------------------- |
    |                         | gettext                 |
    | dbus-1                  | libdbus-1-dev           |
    | exo-2                   | libexo-2-dev            |
    | expat                   | libexpat1-dev           |
    | gdk-pixbuf-2.0          | libgdk-pixbuf-2.0-dev   |
    | glib-2.0                | libglib2.0-dev          |
    | gtk+-2.0                | libgtk2.0-dev           |
    | gtk+-3.0                | libgtk-3-dev            |
    | gumbo                   | libgumbo-dev            |
    | mount                   | libmount-dev            |
    | libnotify               | libnotify-dev           |
    | libpcre                 | libpcre3-dev (pcre)     |
    | libpcre2-8              | libpcre2-dev (pcre2)    |
    | libpng                  | libpng-dev              |
    | polkit-gobject-1        | libpolkit-gobject-1-dev |
    | tinyxml                 | libtinyxml-dev          |
    | libusb                  | libusb-dev              |
    | libwnck-3.0             | libwnck-3-dev           |
    | x11                     | libx11-dev              |
    | libxfce4ui-2            | libxfce4ui-2-dev        |
    | libxfce4util-1.0        | libxfce4util-dev        |
    | libxfconf-0             | libxfconf-0-dev         |
    | libxml-2.0              | libxml2-dev             |
    | z3                      | libz3-dev               |
    | libzen                  | libzen-dev              |


