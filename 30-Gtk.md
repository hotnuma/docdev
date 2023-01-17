**[ [Home](00-Home.html) | [Xfce](05-Xfce.html) | [DBus](10-DBus.html) | [Bash](15-Bash.html) | [Build](20-Build.html) | [Cpp](25-Cpp.html) | Gtk | [Git](35-Git.html) | [Other](99-Other.html) ]**

## Gtk

---

#### Reference

* Docs
    
    https://developer-old.gnome.org/gtk3/stable/  
    https://www.manpagez.com/html/gtk3/gtk3-3.24.31/index.php  
    https://www.manpagez.com/html/glib/glib-2.56.0/index.php  
    https://www.manpagez.com/html/gio/gio-2.56.0/index.php  

* Gtk3 Git
    
    https://gitlab.gnome.org/GNOME/gtk/-/commits/gtk-3-24/  

* Gtk/Glib version
    
    https://askubuntu.com/questions/78377/  
    
    `dpkg -l libglib2.0-0 libgtk-3-0 | grep ^ii`  

* Build simple program
    
    ```
    gcc -o gtksimple gtksimple.c `pkg-config --libs --cflags gtk+-3.0`
    ```



#### Tutorial

* DnD
    
    https://wiki.gnome.org/Newcomers/OldDragNDropTutorial  
    
* Gtk
    
    https://zetcode.com/gui/gtk2/  
    [https://www.cc.gatech.edu/.../gtk_tut.html](https://www.cc.gatech.edu/data_files/public/doc/gtk/tutorial/gtk_tut.html)  
    https://gitlab.gnome.org/GNOME/gtk/-/tree/gtk-3-24/examples  
    https://toshiocp.github.io/Gtk4-tutorial/  

* GApplication
    
    [https://github.com/bratsche/glib/blob/master/gio/tests/gappl](https://github.com/bratsche/glib/blob/master/gio/tests/gapplication-example-cmdline2.c)

* GtkApplication
    
    https://www.manpagez.com/html/gtk3/gtk3-3.24.31/ch01s04.php  
    https://stackoverflow.com/questions/52492939/  
    [https://stackoverflow.com/questions/19072161/](https://stackoverflow.com/questions/19072161/preventing-multiple-instances-of-a-gtk-application)  
    https://developer.gnome.org/documentation/tutorials/application.html  

* TreeView

    https://docs.gtk.org/gtk3/treeview-tutorial.html  
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

* gudev example
    
    https://gist.github.com/fourdollars/6410173



#### Articles

* Gtk3-classic
    
    https://github.com/lah7/gtk3-classic  


