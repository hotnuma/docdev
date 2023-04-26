**[ [Home](00-Home.html) | [Xfce](05-Xfce.html) | [DBus](10-DBus.html) | [Bash](15-Bash.html) | [Build](20-Build.html) | [Cpp](25-Cpp.html) | Gtk | [Git](35-Git.html) | [Other](99-Other.html) ]**

## Gtk

---

#### Reference

* Docs

    <form action="https://google.com/search" method="get">
        <input type="hidden" name="sitesearch" value="developer-old.gnome.org" />
        <input type="text" placeholder="Search Gtk..." name="q" />
        <button>Search</button>
    </form>
    
    [developer-old-gtk-3.24](https://developer-old.gnome.org/gtk3/3.24/)  
    [developer-old-gobject](https://developer-old.gnome.org/gobject/stable/index.html)  
    [manpagez-glib-2.56](https://www.manpagez.com/html/glib/glib-2.56.0/index.php)  
    [manpagez-gio-2.56](https://www.manpagez.com/html/gio/gio-2.56.0/index.php)  
    [icon-naming](https://specifications.freedesktop.org/icon-naming-spec/latest/ar01s04.html)  
    
* Tutorial
    
    [zetcode-gtk2](https://zetcode.com/gui/gtk2/)  
    [gtk3-tutorial](https://github.com/RainMark/gtk3-tutorial/tree/master/_examples)  
    [python-gtk-3-tutorial](https://python-gtk-3-tutorial.readthedocs.io/en/latest/gallery.html)  
    [gtk-tutorial](https://www.cc.gatech.edu/data_files/public/doc/gtk/tutorial/gtk_tut.html)  
    [gtk4-tutorial](https://toshiocp.github.io/Gtk4-tutorial/)  

* Build simple program
    
    ```
    gcc -o gtksimple gtksimple.c `pkg-config --libs --cflags gtk+-3.0`
    ```

* Gtk/Glib version
    
    https://askubuntu.com/questions/78377/  
    
    `dpkg -l libglib2.0-0 libgtk-3-0 | grep ^ii`  



#### Tutorial

* GObject
    
    https://docs.gtk.org/gobject/tutorial.html  

* g_object_new and matching g_object_unref
    
    https://stackoverflow.com/questions/2848273/  

* How to properly add images to buttons
    
    [https://discourse.gnome.org/t/how-to-properly-add-images-to-](https://discourse.gnome.org/t/how-to-properly-add-images-to-buttons/1185/2)  

* TreeView

    [gtk3-treeview-tutorial](https://docs.gtk.org/gtk3/treeview-tutorial.html)  
    [zetcode-gtk2-treeview](https://zetcode.com/gui/gtk2/gtktreeview/)  
    [wikibooks-gtk-treeview](https://en.wikibooks.org/wiki/GTK%2B_By_Example/Tree_View/Tree_Models)  
    
* Toolbar
    
    [add-gtkwidget](https://stackoverflow.com/questions/10740967/how-to-add-gtkwidget-to-gtktoolbar)  

* DnD
    
    https://wiki.gnome.org/Newcomers/OldDragNDropTutorial  
    
* GtkBox vs GtkGrid
    
    https://www.manpagez.com/html/gtk3/gtk3-3.24.31/ch30s02.php  


