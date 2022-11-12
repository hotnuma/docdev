**[ [Home](00-Home.html) | Xfce | [Thunar](02-Thunar.html) | [Gtk](03-Gtk.html) | [Cpp](07-Cpp.html) | [Bash](06-Bash.html) | [Build](04-Build.html) | [Git](05-Git.html) | [Other](99-Other.html) ]**

## Xfce

---

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



#### Environment
    
* Xdg
    
    ```
    $XDG_CONFIG_DIRS
    ```



#### Directories

* Xdg
    
    ```
    /etc/xdg/
    /etc/xdg/xdg-xubuntu/
    ```

* Applications

    ```
    $HOME/.local/share/applications
    /usr/share/applications
    /usr/local/share/applications/
    ```

* Default config
    
    ```
    /etc/skel/.config
    ```

* Config
    
    ```
    $HOME/.config/xfce4/
    ```

* Themes
    
    ```
    $HOME/.themes/
    ```

* Wallpapers

    ```
    $HOME/.local/share/xfce4/backdrops/
    /usr/share/backgrounds/
    /usr/share/xfce4/backdrops/
    /usr/share/xfce4/backdrops/xfce/
    ```



#### Config files

* Xdg menu
    
    ```
    /etc/xdg/xdg-xubuntu/menus/xfce-applications.menu
    /etc/xdg/menus/xfce-applications.menu
    ```
    
* Keyboard shortcuts
    
    ```
    $HOME/.config/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml
    /etc/xdg/xdg-xubuntu/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml
    /etc/xdg/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml
    ```

* Prefered applications

    ```
    /etc/xdg/xfce4/helpers.rc
    ```
    
* Profile

    ```
    /etc/environment
    /etc/profile
    $HOME/.profile
    ```



#### Startup

* init

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
    
* lightdm
    
    Show configuration : lightdm --show-config
    
    Config file : /etc/lightdm/lightdm.conf
    
    Default session : /usr/share/lightdm/lightdm.conf.d/60-xubuntu.conf
    
* Desktop sessions
    
    https://askubuntu.com/questions/77191/  
    
    See desktop files in /usr/share/xsessions directory
    
* xfce4-session settings

    ```
    /etc/xdg/xdg-xubuntu/xfce4/xfconf/xfce-perchannel-xml/xfce4-session.xml
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

* XF86keysym
    
    https://unix.stackexchange.com/questions/426977/  


