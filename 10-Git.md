<link href="style.css" rel="stylesheet"></link>

**[ [Home](00-Home.html) | [Build](05-Build.html) | Git | [Bash](15-Bash.html) | [Cpp](25-Cpp.html) | [Gtk](30-Gtk.html) | [Other](99-Other.html) ]**

## Git

---

#### Basics

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

#### History

* Reset last changes
    
    https://stackoverflow.com/questions/4630312/  
    
* Commit history
    
    https://git-scm.com/book/en/v2/Git-Basics-Viewing-the-Commit-History  
    
    example : `git log --pretty=oneline --since=2021-03-21`

* Diff from commit
    
    https://stackoverflow.com/questions/17563726/  
    
    `git diff COMMIT~ COMMIT`

#### Configuration

* Generate access token
    
    https://docs.github.com/en/github/authenticating-to-github/creating-a-personal-access-token  

* Configure line endings
    
    [https://docs.github.com/en/github/...](https://docs.github.com/en/github/getting-started-with-github/configuring-git-to-handle-line-endings)  


