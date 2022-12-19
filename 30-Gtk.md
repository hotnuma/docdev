**[ [Home](00-Home.html) | [Xfce](05-Xfce.html) | [DBus](10-DBus.html) | [Bash](15-Bash.html) | [Build](20-Build.html) | [Cpp](25-Cpp.html) | Gtk | [Git](35-Git.html) | [Other](99-Other.html) ]**

## Gtk

---

#### Reference

* Docs
    
    https://www.manpagez.com/html/gtk3/gtk3-3.24.31/index.php  
    https://developer-old.gnome.org/gtk3/stable/  
    https://www.manpagez.com/html/glib/glib-2.56.0/index.php  
    https://www.manpagez.com/html/gio/gio-2.56.0/index.php  

* Gtk/Glib version
    
    https://askubuntu.com/questions/78377/  
    
    `dpkg -l libglib2.0-0 libgtk-3-0 | grep ^ii`  

* Valgrind
    
    https://valgrind.org/docs/manual/quick-start.html  
    https://developer.gnome.org/documentation/tools/valgrind.html  
    [https://stackoverflow.com/questions/16659781/](https://stackoverflow.com/questions/16659781/memory-leaks-in-gtk-hello-world-program)  
    https://wiki.wxwidgets.org/Valgrind_Suppression_File_Howto  
    
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

#### Tutorial

* Gtk
    
    https://zetcode.com/gui/gtk2/  
    [https://www.cc.gatech.edu/.../gtk_tut.html](https://www.cc.gatech.edu/data_files/public/doc/gtk/tutorial/gtk_tut.html)  
    https://gitlab.gnome.org/GNOME/gtk/-/tree/gtk-3-24/examples  
    https://toshiocp.github.io/Gtk4-tutorial/  

* GtkApplication
    
    https://www.manpagez.com/html/gtk3/gtk3-3.24.31/ch01s04.php  
    https://stackoverflow.com/questions/52492939/  
    [https://stackoverflow.com/questions/19072161/](https://stackoverflow.com/questions/19072161/preventing-multiple-instances-of-a-gtk-application)  
    https://developer.gnome.org/documentation/tutorials/application.html  

* TreeView

    http://scentric.net/tutorial/  
    https://zetcode.com/gui/gtk2/gtktreeview/  
    https://en.wikibooks.org/wiki/GTK%2B_By_Example/Tree_View/Tree_Models  

* Custom Widgets

    https://www.cc.gatech.edu/data_files/public/doc/gtk/tutorial/gtk_tut-20.html  

* Stock items
    
    http://www.manpagez.com/html/gtk3/gtk3-3.20.2/gtk3-Stock-Items.php  
    
* GtkGrid

    https://stackoverflow.com/questions/18513921/  

* GtkNotebook

    https://mail.gnome.org/archives/gtk-app-devel-list/2017-May/msg00037.html  
    https://stackoverflow.com/questions/8850043/  

* Redirect stdout to GtkTextView
    
    https://mail.gnome.org/archives/gtk-list/2006-February/msg00040.html  

* GtkFileChooserDialog
    
    https://www.gnu.org/software/guile-gnome/docs/gtk/html/GtkFileChooserDialog.html  



#### Articles

* Gtk3-classic
    
    https://github.com/lah7/gtk3-classic  

* GtkTreeView Memory leak
    
    https://bugzilla.redhat.com/show_bug.cgi?id=1965195  
    [https://gitlab.gnome.org/GNOME/gtk/-/commit/21f8098261486417](https://gitlab.gnome.org/GNOME/gtk/-/commit/21f8098261486417db371b202bc0494c12017468)  
    https://gitlab.gnome.org/GNOME/gtk/-/pipelines/289296  
    https://gitlab.gnome.org/GNOME/gtk/-/merge_requests/3660  


