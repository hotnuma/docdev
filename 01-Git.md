**[ [Home](00-Home.html) | [Build](01-Build.html) | Git | [Bash](02-Bash.html) | [Cpp](03-Cpp.html) | [Gtk](05-Gtk.html) ]**

## Git

---

* Basics

    [Git status doesn’t know if your local repository is out of date · Mike F. Robbins](https://mikefrobbins.com/2016/02/18/git-status-doesnt-know-if-your-local-repository-is-out-of-date/)

    [les commandes Git que vous devez absolument connaitre!](https://www.hostinger.fr/tutoriels/commandes-git)

    [Access token](https://docs.github.com/en/github/authenticating-to-github/creating-a-personal-access-token)

    [An Intro to Git](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)

    [Authenticate Token](https://stackoverflow.com/questions/18935539/authenticate-with-github-using-a-token)

    [Git Guide](https://github.com/git-guides/)

    [Line endings](https://docs.github.com/en/github/getting-started-with-github/configuring-git-to-handle-line-endings)

    [Main vs Master](https://stackoverflow.com/questions/64249491/difference-between-main-branch-and-master-branch-in-github)

    [Remote Origin](https://stackoverflow.com/questions/6565357/git-push-requires-username-and-password)

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

