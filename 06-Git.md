**[ [Home](00-Home.html) | [Xfce](01-Xfce.html) | [Bash](02-Bash.html) | [Build](03-Build.html) | [Cpp](04-Cpp.html) | [Gtk](05-Gtk.html) | Git | [Other](99-Other.html) ]**

## Git

---

#### Commands

* clone

    ```
    git clone https://OAUTH_KEY@github.com/hotnuma/libtinycpp.git
    git clone https://github.com/hotnuma/libtinycpp.git
    git clone -b master --single-branch https://github.com/hotnuma/libtinycpp.git
    ```

* clone a specific tag

    ```
    git clone --depth 1 --branch thunar-4.16.6 https://gitlab.xfce.org/xfce/thunar.git
    ```

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

* Commit history
    
    https://git-scm.com/book/en/v2/Git-Basics-Viewing-the-Commit-History  

* Generate access token
    
    https://docs.github.com/en/github/authenticating-to-github/creating-a-personal-access-token  

* Configure line endings
    
    [https://docs.github.com/en/github/...](https://docs.github.com/en/github/getting-started-with-github/configuring-git-to-handle-line-endings)  


