**[ Home | [Xfce](05-Xfce.html) | [DBus](10-DBus.html) | [Bash](15-Bash.html) | [Build](20-Build.html) | [Cpp](25-Cpp.html) | [Gtk](30-Gtk.html) | [Git](35-Git.html) | [Other](99-Other.html) ]**

## Docs Dev

---

#### Libraries

    libgudev : libgudev-1.0-dev
    pcre : libpcre3-dev
    pcre2 : libpcre2-dev
    libxml2 : libxml2-dev


#### Freedesktop

* Icon names
    
    https://specifications.freedesktop.org/icon-naming-spec/latest/ar01s04.html  



#### Markdown

* docs
    
    https://www.markdownguide.org/basic-syntax/  
    [https://github.com/adam-p/markdown-here/...](https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet)  
    [https://docs.github.com/en/github/writing-on-github/...](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)  
    https://commonmark.org/  

* parsers
    
    https://github.com/hoedown/hoedown  
    https://github.com/faelys/libsoldout  
    https://github.com/commonmark/cmark  
    https://github.com/Orc/discount  



#### Tools

* astyle
    
    One file : `astyle -n --style=allman thunar-window.c`

    Recursive : `astyle -nr --style=allman "test/*.h" "test/*.c"`

* Valgrind
    
    https://valgrind.org/docs/manual/quick-start.html  
    https://developer.gnome.org/documentation/tools/valgrind.html  
    [https://stackoverflow.com/questions/16659781/](https://stackoverflow.com/questions/16659781/memory-leaks-in-gtk-hello-world-program)  
    https://wiki.wxwidgets.org/Valgrind_Suppression_File_Howto  
    [https://discourse.gnome.org/t/after-freeing-a-garray-valgrin](https://discourse.gnome.org/t/after-freeing-a-garray-valgrind-still-complains-about-non-freed-blocks/3378/1)  
    [https://discourse.gnome.org/t/how-to-correct-read-ini-files-](https://discourse.gnome.org/t/how-to-correct-read-ini-files-using-glib/6987)  
    
    ```
    /usr/lib/valgrind/debian.supp
    /usr/lib/valgrind/ncurses.supp
    /usr/lib/valgrind/python3.supp
    /usr/libexec/valgrind/default.supp
    /usr/share/gtk-3.0/valgrind/gtk.supp
    /usr/share/glib-2.0/valgrind/glib.supp
    /home/hotnuma/DevSrc/autre/gtk+3.0-3.24.25/gtk.supp
    /home/hotnuma/DevSrc/glib-2.68.1/glib.supp
    ```



#### /proc fs

* References
    
    https://fr.wikipedia.org/wiki/Procfs  
    [https://mtodorovic.developpez.com/linux/...](https://mtodorovic.developpez.com/linux/programmation-avancee/?page=page_7)  
    https://github.com/pixelb/ps_mem  
    https://gitlab.com/procps-ng/procps  
    https://gitlab.gnome.org/GNOME/libgtop  
    https://github.com/htop-dev/htop/  
    
* Memory usage
    
    https://stackoverflow.com/questions/41224738/  
    [https://github.com/lxde/lxpanel/](https://github.com/lxde/lxpanel/blob/master/plugins/monitors/monitors.c#L296)  


