**[ [Home](00-Home.html) | Build | [Git](01-Git.html) | [Bash](02-Bash.html) | [Cpp](03-Cpp.html) | [Gtk](05-Gtk.html) ]**

## Build

---



#### Reference

* Basics
    
    https://wiki.debian.org/BuildingTutorial  



#### Dependencies

* Find build dependencies

    https://askubuntu.com/questions/172367/  
    
    ```
    apt search procps
    ```
    
    ```
    sudo apt-get build-dep --dry-run thunar
    ```
    
* Find program dependencies
    
    https://unix.stackexchange.com/questions/120015/

* fix library error

    ```
    sudo /sbin/ldconfig -v
    ```

* pkg-config

    ```
    pkg-config --libs --cflags gtk+-3.0
    pkg-config --modversion glib-2.0
    ```


#### Meson

* Basics
    
    https://mesonbuild.com/IndepthTutorial.html  

* Include a pre-compiled library
    
    https://stackoverflow.com/questions/67925406/  

* Porting projects
    
    https://mesonbuild.com/Porting-from-autotools.html  
    https://nibblestew.blogspot.com/2016/09/how-to-convert-autotools-project-to.html  
    https://github.com/mesonbuild/meson/blob/master/tools/ac_converter.py  
    https://github.com/mesonbuild/meson/blob/master/tools/cmake2meson.py  


