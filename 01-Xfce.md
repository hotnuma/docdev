**[ [Home](00-Home.html) | Xfce | [Thunar](02-Thunar.html) | [Gtk](03-Gtk.html) | [Build](04-Build.html) | [Git](05-Git.html) | [Git](05-Git.html) | [Bash](06-Bash.html) | [Cpp](07-Cpp.html) ]**

## Xfce

---

#### Links

* home
    
    https://developer.xfce.org/  
    
    https://gitlab.xfce.org/groups/xfce/-/activity  
    https://discourse.gnome.org/latest  

    https://gitlab.xfce.org/xfce  
    https://forum.xfce.org/search.php?action=show_recent  
    https://www.reddit.com/r/xfce/  
    
    https://mail.xfce.org/pipermail/xfce4-dev/  
    https://mail.xfce.org/pipermail/xfce/  



#### Core Libraries

* libxfce4util
    
    https://developer.xfce.org/libxfce4util/index.html  
    https://docs.xfce.org/xfce/libxfce4util/start  
    https://gitlab.xfce.org/xfce/libxfce4util  
    
* libxfce4ui
    
    https://developer.xfce.org/libxfce4ui/index.html  
    https://docs.xfce.org/xfce/libxfce4ui/start  
    https://gitlab.xfce.org/xfce/libxfce4ui  

* exo
    
    https://developer.xfce.org/exo/index.html  
    https://docs.xfce.org/xfce/exo/start  
    https://gitlab.xfce.org/xfce/exo  



#### Startup

* lightdm

    ```
    /sbin/ini
        
        graphical.target

        lightdm
            Xorg
            lightdm --session-child
                xfce4-session
        
        agetty
        systemd/systemd --user
    ```

* Default session
    
    https://askubuntu.com/questions/77191/  
    
    ```
    See desktop files in /usr/share/xsessions directory
    ```
    
* xfce4-session settings

    ```
    /etc/xdg/xfce4/xfconf/xfce-perchannel-xml/xfce4-session.xml
    ```

* feh
    
    ```
    feh --bg-scale /usr/share/rpd-wallpaper/clouds.jpg
    ```

#### Other

* xfconf-query
    
    https://docs.xfce.org/xfce/xfconf/xfconf-query  
    [http://manpages.ubuntu.com/manpages/...](http://manpages.ubuntu.com/manpages/bionic/man1/xfconf-query.1.html)  

* Prefered applications

    ```
    cat /etc/xdg/xfce4/helpers.rc
    ```

* XF86keysym
    
    https://unix.stackexchange.com/questions/426977/  


