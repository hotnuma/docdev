<link href="style.css" rel="stylesheet"></link>

**[ Home | [DBus](10-DBus.html) | [Bash](15-Bash.html) | [Build](20-Build.html) | [Cpp](25-Cpp.html) | [Gtk](30-Gtk.html) | [Git](35-Git.html) | [Other](99-Other.html) ]**

## Docs Dev

---

#### Freedesktop

* Specification
    
    [freedesktop-desktop-entry](https://specifications.freedesktop.org/desktop-entry-spec/desktop-entry-spec-latest.html)  
    [freedesktop-icon-naming](https://specifications.freedesktop.org/icon-naming-spec/latest/ar01s04.html)  


#### Patches

* patch
    
    try : `patch --dry-run -p 1 -i '../dir/my_file.patch'`
    
    do  : `patch -p 1 -i '../dir/my_file.patch'`


#### Markdown

* Syntax
    
    [markdown-here-cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet)  
    [markdownguide-basic-syntax](https://www.markdownguide.org/basic-syntax/)  
    [codecademy-markdown-tables](https://www.codecademy.com/resources/docs/markdown/tables)  
    [writing-on-github](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)  



#### Code Formatting

* astyle
    
    One file : `astyle -n --style=allman thunar-window.c`

    Recursive : `astyle -nr --style=allman "test/*.h" "test/*.c"`

* clang-format
    
    https://clang.llvm.org/docs/ClangFormatStyleOptions.html  
    
    dump config : `clang-format -style=llvm -dump-config > _clang-format`  
    in current dir : `clang-format -i -style=WebKit *.c *.h`  
    
* Other
    
    [awesome-code-formatters](https://github.com/rishirdua/awesome-code-formatters)  
    [uncrustify](https://uncrustify.sourceforge.net/)  
    [clang-format](https://clang.llvm.org/docs/ClangFormat.html)  
    [gnu-indent](https://www.gnu.org/software/indent/)  



#### Libraries

* Packages Names

    | Package Name            | PkgConfig               |
    | :---------------------- | :---------------------- |
    | gettext                 |                         |
    | libdbus-1-dev           | dbus-1                  |
    | libexiv2-dev            | exiv2                   |
    | libexo-2-dev            | exo-2                   |
    | libexpat1-dev           | expat                   |
    | libgdk-pixbuf-2.0-dev   | gdk-pixbuf-2.0          |
    | libglib2.0-dev          | glib-2.0                |
    | libgtk2.0-dev           |                         |
    | libgtk-3-dev            | gtk+-3.0                |
    | libgudev-1.0-dev        | gudev-1.0               |
    | libgumbo-dev            | gumbo                   |
    | libmount-dev            | mount                   |
    | libnotify-dev           | libnotify               |
    | libpcre3-dev (pcre)     | libpcre                 |
    | libpcre2-dev (pcre2)    | libpcre2-8              |
    | libpng-dev              | libpng                  |
    | libpolkit-gobject-1-dev | polkit-gobject-1        |
    | libprocps-dev           | libprocps               |
    | libsm-dev               | sm                      |
    | libthunarx-3-dev        | thunarx-3               |
    | libtinyxml-dev          | tinyxml                 |
    | libusb-dev              | libusb                  |
    | libwnck-3-dev           | libwnck-3.0             |
    | libx11-dev              | x11                     |
    | libxfce4ui-2-dev        | libxfce4ui-2            |
    | libxfce4util-dev        | libxfce4util-1.0        |
    | libxfconf-0-dev         | libxfconf-0             |
    | libxml2-dev             | libxml-2.0              |
    | libxmu-dev              | xmu                     |
    | libz3-dev               | z3                      |
    | libzen-dev              | libzen                  |


