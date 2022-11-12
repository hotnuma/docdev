**[ [Home](00-Home.html) | [Xfce](01-Xfce.html) | Thunar | [Gtk](03-Gtk.html) | [Cpp](07-Cpp.html) | [Bash](06-Bash.html) | [Build](04-Build.html) | [Git](05-Git.html) | [Other](99-Other.html) ]**

## Thunar

---

* Docs
    
    https://developer.xfce.org/thunar/index.html  
    
    https://docs.xfce.org/xfce/thunar/start  
    https://wiki.xfce.org/thunar/dev/build_and_run  
    
* Git
    
    https://gitlab.xfce.org/xfce/thunar  
    
* Custom Actions
    
    https://docs.xfce.org/xfce/thunar/4.12/custom-actions  

* thunar-window.c
    
    292: ThunarWindow object (GtkWindow)

    604: thunar_window_init ()

    creation of app window with all widgets
    
    ```
    GtkWindow window
        GtkGrid grid
            ___________________________________________________
            GtkMenubar menubar
            GtkInfobar infobar (root warning)
            GtkToolbar location_toolbar
                GtkToolItem tool_item
                    ThunarLocationBar location_bar
            ___________________________________________________
            GtkPaned paned (horizontal)
            pane1
                thunar_window_install_sidepane
                ThunarSidePane sidepane
            pane2
                GtkGrid view_box
                    GtkNotebook notebook
                    GtkStatusbar statusbar
            ___________________________________________________
    ```



* ./thunar/thunar-details-view.c
    
    206: thunar_details_view_init
    
    tree_view = exo_tree_view_new ();

    click in the detail view
    
    646: thunar_details_view_button_press_event



* ./thunar/thunar_list_model.c
    
    
* ./thunar/thunar_file.c
    
    :973:thunar_file_info_reload.c

    ```
        file->collate_key = g_utf8_collate_key_for_filename (file->display_name, -1);
    ```
    
    :4144:thunar_file_compare_by_name


