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
    https://developer-old.gnome.org/gobject/stable/index.html  
    https://www.manpagez.com/html/glib/glib-2.56.0/index.php  
    https://www.manpagez.com/html/gio/gio-2.56.0/index.php  
    https://specifications.freedesktop.org/icon-naming-spec/latest/ar01s04.html  
    
* Tutorial
    
    https://zetcode.com/gui/gtk2/  
    https://github.com/RainMark/gtk3-tutorial/tree/master/_examples  
    https://python-gtk-3-tutorial.readthedocs.io/en/latest/gallery.html  
    [https://www.cc.gatech.edu/.../gtk_tut.html](https://www.cc.gatech.edu/data_files/public/doc/gtk/tutorial/gtk_tut.html)  
    https://toshiocp.github.io/Gtk4-tutorial/  

* Build simple program
    
    ```
    gcc -o gtksimple gtksimple.c `pkg-config --libs --cflags gtk+-3.0`
    ```

* Gtk/Glib version
    
    https://askubuntu.com/questions/78377/  
    
    `dpkg -l libglib2.0-0 libgtk-3-0 | grep ^ii`  



#### Tutorial

* GObject Tutorial
    
    https://docs.gtk.org/gobject/tutorial.html  

* g_object_new and matching g_object_unref
    
    [https://stackoverflow.com/questions/2848273/should-a-g-objec](https://stackoverflow.com/questions/2848273/should-a-g-object-new-have-a-matching-g-object-unref)  

* How to properly add images to buttons
    
    [https://discourse.gnome.org/t/how-to-properly-add-images-to-](https://discourse.gnome.org/t/how-to-properly-add-images-to-buttons/1185/2)  

* TreeView

    https://docs.gtk.org/gtk3/treeview-tutorial.html  
    https://zetcode.com/gui/gtk2/gtktreeview/  
    https://en.wikibooks.org/wiki/GTK%2B_By_Example/Tree_View/Tree_Models  
    
* Toolbar
    
    [stackoverflow : add widgets](https://stackoverflow.com/questions/10740967/how-to-add-gtkwidget-to-gtktoolbar)  

* DnD
    
    https://wiki.gnome.org/Newcomers/OldDragNDropTutorial  
    
* GtkBox vs GtkGrid
    
    https://www.manpagez.com/html/gtk3/gtk3-3.24.31/ch30s02.php  


