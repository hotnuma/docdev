**[ [Home](00-Home.html) | [Xfce](01-Xfce.html) | [Thunar](02-Thunar.html) | [Gtk](03-Gtk.html) | [Build](04-Build.html) | Git | [Bash](06-Bash.html) | [Cpp](07-Cpp.html) ]**

## Git

---

* Push an existing repository
    
    ```
    git remote add origin https://OAUTH_KEY@github.com/hotnuma/testcmd.git
    git branch -M master
    git push -u origin master
    ```

* Check Remote

    ```
    git remote -v
    ```

* Remove subdirs

    ```
    git rm -r --cached autre
    ```

* clone

    ```
    git clone https://github.com/hotnuma/libtinycpp.git
    git clone https://OAUTH_KEY@github.com/hotnuma/libtinycpp.git
    git clone -b master --single-branch https://github.com/hotnuma/libtinycpp.git
    ```

* clone a specific tag

    ```
    git clone --depth 1 --branch thunar-4.16.6 https://gitlab.xfce.org/xfce/thunar.git
    ```


