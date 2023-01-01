**[ [Home](00-Home.html) | Xfce | [DBus](10-DBus.html) | [Bash](15-Bash.html) | [Build](20-Build.html) | [Cpp](25-Cpp.html) | [Gtk](30-Gtk.html) | [Git](35-Git.html) | [Other](99-Other.html) ]**

## Xfce

---

#### Reference

* Links
    
    https://forum.xfce.org/search.php?action=show_recent  
    https://www.reddit.com/r/xfce/  
    
    https://gitlab.xfce.org/xfce  
    https://developer.xfce.org/  

* libxfce4ui
    
    https://developer.xfce.org/libxfce4ui/index.html  
    https://docs.xfce.org/xfce/libxfce4ui/start  



#### Xdg
    
* Environment
    
    ```
    $XDG_CONFIG_DIRS : /etc/xdg/xdg-xubuntu:/etc/xdg
    ```

* XFCE Config
    
    ```
    $HOME/.config/xfce4/
    /etc/xdg/xfce4/
    /etc/xdg/xdg-xubuntu/xfce4/
    ```

* xfce4-session settings

    ```
    /etc/xdg/xfce4/xfconf/xfce-perchannel-xml/xfce4-session.xml
    /etc/xdg/xdg-xubuntu/xfce4/xfconf/xfce-perchannel-xml/xfce4-session.xml
    ```

* Prefered applications

    ```
    /etc/xdg/xfce4/helpers.rc
    ```
    
* Xdg menu
    
    ```
    /etc/xdg/xdg-xubuntu/menus/xfce-applications.menu
    /etc/xdg/menus/xfce-applications.menu
    ```

* Keyboard shortcuts
    
    ```
    $HOME/.config/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml
    /etc/xdg/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml
    /etc/xdg/xdg-xubuntu/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml
    ```

* XF86 Multimedia Keys
    
    https://unix.stackexchange.com/questions/426977/  



#### Share

* Desktop sessions
    
    `/usr/share/xsessions/`
    
    https://askubuntu.com/questions/77191/  
    
* Applications

    ```
    $HOME/.local/share/applications/
    /usr/share/applications/
    /usr/local/share/applications/
    ```

* Wallpapers

    ```
    $HOME/.local/share/xfce4/backdrops/
    /usr/share/backgrounds/
    /usr/share/xfce4/backdrops/
    /usr/share/xfce4/backdrops/xfce/
    ```



#### Other

* Profile

    ```
    /etc/environment
    $HOME/.profile
    /etc/profile
    ```

* xfconf-query
    
    https://docs.xfce.org/xfce/xfconf/xfconf-query  
    [http://manpages.ubuntu.com/manpages/...](http://manpages.ubuntu.com/manpages/bionic/man1/xfconf-query.1.html)  

* Thunar Custom Actions
    
    https://docs.xfce.org/xfce/thunar/4.12/custom-actions  
    https://forum.xfce.org/viewtopic.php?id=12633  
    
    ```
    xfce4-terminal -e 'bash -c "extract.sh %f; bash"'
    ```

* Default config
    
    ```
    /etc/skel/.config
    ```

* Themes
    
    ```
    $HOME/.themes/
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
    
    Show configuration : `lightdm --show-config`
    
    Config file : `/etc/lightdm/lightdm.conf`
    
    Default session : `/usr/share/lightdm/lightdm.conf.d/60-xubuntu.conf`

* Desktop background
    
    ```
    hsetroot -solid '#5e5c64'
    ```

    ```
    feh --bg-scale /usr/share/rpd-wallpaper/clouds.jpg
    ```



#### Articles

* Gtk File Chooser
    
    https://gitlab.xfce.org/xfce/thunar/-/issues/547  
    [https://www.reddit.com/r/xfce/comments/kk8xo5/file_chooser_b](https://www.reddit.com/r/xfce/comments/kk8xo5/file_chooser_buttons_in_csd_titlebar_not_of/)  
    [https://superuser.com/questions/944119/replace-gtk-file-dial](https://superuser.com/questions/944119/replace-gtk-file-dialog-with-alternative)  

* Xfce Classic Fork
    
    [https://www.linuxadictos.com/en/xfce-classic](https://www.linuxadictos.com/en/xfce-classic-a-fork-of-xfce-but-without-the-client-side-window-decoration.html)  

* xfwm4 creates input lag
    
    https://gitlab.xfce.org/xfce/xfwm4/-/issues/679#note_60519  

* Port to Wayland
    
    [https://gitlab.xfce.org/xfce/xfce4-panel/-/merge_requests/10](https://gitlab.xfce.org/xfce/xfce4-panel/-/merge_requests/103#note_60758)  

<!--
    https://mail.xfce.org/pipermail/xfce4-dev/  
    https://mail.xfce.org/pipermail/xfce/  
-->


