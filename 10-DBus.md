**[ [Home](00-Home.html) | [Xfce](05-Xfce.html) | DBus | [Bash](15-Bash.html) | [Build](20-Build.html) | [Cpp](25-Cpp.html) | [Gtk](30-Gtk.html) | [Git](35-Git.html) | [Other](99-Other.html) ]**

## DBus

---

#### Reference

* Links
    
    https://dbus.freedesktop.org/doc/dbus-specification.html  
    https://www.matthew.ath.cx/misc/dbus  
    https://www.softprayog.in/programming/d-bus-tutorial  
    https://www.youtube.com/watch?v=3ZwzfZgU598  
    https://github.com/flexibeast/guides/blob/master/dbus.md  
    https://unix.stackexchange.com/questions/46301/  

    https://www.freedesktop.org/software/systemd/man/busctl.html  
    https://www.freedesktop.org/software/gstreamer-sdk/data/docs/2012.5/gio/gdbus.html  


* Command Line
    
    List system services : `busctl --no-pager --acquired > sys_dbus.txt`  
    List user services : `busctl --no-pager --user --acquired > sys_dbus_user.txt`  
    
    Monitor UDisk2 : `sudo busctl monitor org.freedesktop.UDisks2`  

* Notifications
    
    https://specifications.freedesktop.org/notification-spec/notification-spec-latest.html  
    
    https://superuser.com/questions/1592674/  
    
* Examples
    
    [https://github.com/wware/stuff/.../dbus-example.c](https://github.com/wware/stuff/blob/master/dbus-example/dbus-example.c)  
    https://gist.github.com/dradtke/4949546  



#### Articles

* Links

    https://www.freedesktop.org/wiki/Software/dbus/  
    https://sheitsandgiggles.com/2019/07/16/a-trip-into-dbus-send/  
    https://stackoverflow.com/questions/43118430/  

    https://unix.stackexchange.com/questions/46301/a-list-of-available-d-bus-services  
    https://www.freedesktop.org/software/gstreamer-sdk/data/docs/2012.5/gio/gdbus.html  
    https://manpages.ubuntu.com/manpages/bionic/man1/gdbus.1.html  

    http://www.kaizou.org/2014/06/dbus-command-line.html  
    https://stackoverflow.com/questions/3684999/  
    [https://developer.ridgerun.com/wiki/...](https://developer.ridgerun.com/wiki/index.php/How_to_send_Dbus_messages_manually)  

* Ian&#39;s TechBlog: Six ways to make a notification pop-up
    
    [http://cheesehead-techblog.blogspot.com/2009/02/five-ways-to](http://cheesehead-techblog.blogspot.com/2009/02/five-ways-to-make-notification-pop-up.html)

* linux - How to clear notification sent by shell script - Super User
    
    [https://superuser.com/questions/1592674/how-to-clear-notific](https://superuser.com/questions/1592674/how-to-clear-notification-sent-by-shell-script)

* dbus/dbus-send.c at master · freedesktop/dbus
    
    [https://github.com/freedesktop/dbus/blob/master/tools/dbus-s](https://github.com/freedesktop/dbus/blob/master/tools/dbus-send.c)

* src/dbus-send.c · master · Munju Kang / dbus-send · GitLab
    
    [https://gitlab.com/mujicion/dbus-send/-/blob/master/src/dbus](https://gitlab.com/mujicion/dbus-send/-/blob/master/src/dbus-send.c)

* nowrep/notify-desktop: notify-send clone without external dependencies
    
    https://github.com/nowrep/notify-desktop

* libnotify/notify-send.c at master · GNOME/libnotify
    
    [https://github.com/GNOME/libnotify/blob/master/tools/notify-](https://github.com/GNOME/libnotify/blob/master/tools/notify-send.c)

* fnott/dbus.c sur master - fnott - Codeberg.org
    
    https://codeberg.org/dnkl/fnott/src/branch/master/dbus.c

* D-Bus - Wikipedia
    
    https://en.wikipedia.org/wiki/D-Bus

* Sample program for GDbus signals - Stack Overflow
    
    [https://stackoverflow.com/questions/37185735/sample-program-](https://stackoverflow.com/questions/37185735/sample-program-for-gdbus-signals)

* canonical-system-enablement/udisks2-examples: Example code for interfacing with udisks2
    
    [https://github.com/canonical-system-enablement/udisks2-examp](https://github.com/canonical-system-enablement/udisks2-examples)

* udisks2-examples/detect-hotplug.c at master · canonical-system-enablement/udisks2-examples
    
    [https://github.com/canonical-system-enablement/udisks2-examp](https://github.com/canonical-system-enablement/udisks2-examples/blob/master/detect-hotplug.c)

* UDisks Reference Manual: UDisks Reference Manual
    
    http://storaged.org/doc/udisks2-api/latest/index.html

* udisks: UDisks Reference Manual
    
    http://storaged.org/doc/udisks2-api/latest/udisks.8.html


