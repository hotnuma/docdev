**[ [Home](00-Home.html) | [Xfce](05-Xfce.html) | [DBus](10-DBus.html) | [Bash](15-Bash.html) | [Build](20-Build.html) | [Cpp](25-Cpp.html) | Gtk | [Git](35-Git.html) | [Other](99-Other.html) ]**

## Gtk

---

#### Reference

* Docs
    
    https://developer-old.gnome.org/gtk3/3.24/  
    https://www.manpagez.com/html/glib/glib-2.56.0/index.php  
    https://www.manpagez.com/html/gio/gio-2.56.0/index.php  

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

* TreeView

    https://docs.gtk.org/gtk3/treeview-tutorial.html  
    http://scentric.net/tutorial/  
    https://zetcode.com/gui/gtk2/gtktreeview/  
    https://en.wikibooks.org/wiki/GTK%2B_By_Example/Tree_View/Tree_Models  



#### Tips
    
* Add GtkWidget to GtkToolbar
    
    [https://stackoverflow.com/questions/10740967/how-to-add-gtkw](https://stackoverflow.com/questions/10740967/how-to-add-gtkwidget-to-gtktoolbar)  



#### Gtk

* GTK+ par l'exemple.
    
    [https://nicolasj.developpez.com/gtk/cours/?page=les-raccourc](https://nicolasj.developpez.com/gtk/cours/?page=les-raccourcis-clavier)  

* gtk-examples/accel.c at master · bstpierre/gtk-examples
    
    [https://github.com/bstpierre/gtk-examples/blob/master/c/acce](https://github.com/bstpierre/gtk-examples/blob/master/c/accel.c)  

* C++ (Cpp) gtk_accel_group_connect Examples - HotExamples
    
    [https://cpp.hotexamples.com/examples/-/-/gtk_accel_group_con](https://cpp.hotexamples.com/examples/-/-/gtk_accel_group_connect/cpp-gtk_accel_group_connect-function-examples.html)  



* GtkWrite Text Editor in C and Gtk+2
    
    https://github.com/drankinatty/gtkwrite  

* gtkwrite/gtk_toolbar.c
    
    [https://github.com/drankinatty/gtkwrite/blob/master/gtk_tool](https://github.com/drankinatty/gtkwrite/blob/master/gtk_toolbar.c)  

* Drop down menu to Toolbar Item
    
    [https://stackoverflow.com/questions/9132440/gtk-drop-down-me](https://stackoverflow.com/questions/9132440/gtk-drop-down-menu-to-toolbar-item)  



* GNOME / libdazzle · GitLab
    
    https://gitlab.gnome.org/GNOME/libdazzle  

* How to properly add images to buttons
    
    [https://discourse.gnome.org/t/how-to-properly-add-images-to-](https://discourse.gnome.org/t/how-to-properly-add-images-to-buttons/1185/2)  

* DnD
    
    https://wiki.gnome.org/Newcomers/OldDragNDropTutorial  
    
* GApplication
    
    [https://github.com/bratsche/glib/blob/master/gio/tests/gappl](https://github.com/bratsche/glib/blob/master/gio/tests/gapplication-example-cmdline2.c)

* GtkApplication
    
    https://www.manpagez.com/html/gtk3/gtk3-3.24.31/ch01s04.php  
    https://stackoverflow.com/questions/52492939/  
    [https://stackoverflow.com/questions/19072161/](https://stackoverflow.com/questions/19072161/preventing-multiple-instances-of-a-gtk-application)  
    https://developer.gnome.org/documentation/tutorials/application.html  

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

* Gtk3-classic
    
    https://github.com/lah7/gtk3-classic  

* Compile errors for GTK/Cairo - Raspberry Pi Forums
    
    https://forums.raspberrypi.com/viewtopic.php?t=199626  

* c - How to create a cairo object within a gtk window in GTK+3 - Stack Overflow
    
    [https://stackoverflow.com/questions/57699050/how-to-create-a](https://stackoverflow.com/questions/57699050/how-to-create-a-cairo-object-within-a-gtk-window-in-gtk3)  

* Programming GTK+ GUIs using Glade
    
    http://www.peteronion.org.uk/GtkExamples/GladeTutorials.html  

* gtk - How to create custom widget in GTK3 in C? - Stack Overflow
    
    [https://stackoverflow.com/questions/25824401/how-to-create-c](https://stackoverflow.com/questions/25824401/how-to-create-custom-widget-in-gtk3-in-c)  

* HowDoI/CustomWidgets - GNOME Wiki!
    
    https://wiki.gnome.org/HowDoI/CustomWidgets  

* demos/gtk-demo/pickers.c · 3.19.11 · Ronan Pigott / gtk · GitLab
    
    [https://gitlab.gnome.org/RPigott1/gtk/-/blob/3.19.11/demos/g](https://gitlab.gnome.org/RPigott1/gtk/-/blob/3.19.11/demos/gtk-demo/pickers.c)  

* button - How to center widgets in a grid - GTK C - Stack Overflow
    
    [https://stackoverflow.com/questions/72764326/how-to-center-w](https://stackoverflow.com/questions/72764326/how-to-center-widgets-in-a-grid-gtk-c)  

* Gtk 3.24.26's preedit is breaking accented input on popular websites like WhatsApp, when using Firefox (#5744) · Issues · GNOME / gtk · GitLab
    
    https://gitlab.gnome.org/GNOME/gtk/-/issues/5744  

* c - Gtk3 - How to listen to accelerators via GAction in my GtkApplication? - Stack Overflow
    
    [https://stackoverflow.com/questions/62505092/gtk3-how-to-lis](https://stackoverflow.com/questions/62505092/gtk3-how-to-listen-to-accelerators-via-gaction-in-my-gtkapplication)  

* user interface - Creating a Menu in GTK3+ C - Stack Overflow
    
    [https://stackoverflow.com/questions/28132798/creating-a-menu](https://stackoverflow.com/questions/28132798/creating-a-menu-in-gtk3-c)  

* c - Gtk3: GMenu/GMenuItem: How to sense if a submenu was opened? ( signal of submenus) - Stack Overflow
    
    [https://stackoverflow.com/questions/61840107/gtk3-gmenu-gmen](https://stackoverflow.com/questions/61840107/gtk3-gmenu-gmenuitem-how-to-sense-if-a-submenu-was-opened-signal-of-submenu)  

* c - Howto link GMenu and GtkMenu button in Gtk 3 - Stack Overflow
    
    [https://stackoverflow.com/questions/53360871/howto-link-gmen](https://stackoverflow.com/questions/53360871/howto-link-gmenu-and-gtkmenu-button-in-gtk-3)  

* Icon and tooltip for menu item - Platform - GNOME Discourse
    
    [https://discourse.gnome.org/t/icon-and-tooltip-for-menu-item](https://discourse.gnome.org/t/icon-and-tooltip-for-menu-item/10665)  

* bloatpad.c source code [gtk/examples/bp/bloatpad.c] - Codebrowser
    
    https://codebrowser.dev/gtk/gtk/examples/bp/bloatpad.c.html  

* C++ (Cpp) g_menu_item_new Exemples - HotExamples
    
    [https://cpp.hotexamples.com/fr/examples/-/-/g_menu_item_new/](https://cpp.hotexamples.com/fr/examples/-/-/g_menu_item_new/cpp-g_menu_item_new-function-examples.html)  

* Gtk.ImageMenuItem – gtk+-3.0
    
    https://valadoc.org/gtk+-3.0/Gtk.ImageMenuItem.html  

* c - gtk3: How to propagate key-events/accelerators (shortcuts) from local to global? - Stack Overflow
    
    [https://stackoverflow.com/questions/61388055/gtk3-how-to-pro](https://stackoverflow.com/questions/61388055/gtk3-how-to-propagate-key-events-accelerators-shortcuts-from-local-to-global)  

* GtkAccelLabel: GTK+ 3 Reference Manual
    
    [https://developer-old.gnome.org/gtk3/stable/GtkAccelLabel.ht](https://developer-old.gnome.org/gtk3/stable/GtkAccelLabel.html)  

* c - How to use gtk_widget_add_accelerator? - Stack Overflow
    
    [https://stackoverflow.com/questions/1165974/how-to-use-gtk-w](https://stackoverflow.com/questions/1165974/how-to-use-gtk-widget-add-accelerator)  


