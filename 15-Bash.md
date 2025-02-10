<link href="style.css" rel="stylesheet"></link>

**[ [Home](00-Home.html) | [Build](05-Build.html) | [Git](10-Git.html) | Bash | [Cpp](25-Cpp.html) | [Gtk](30-Gtk.html) | [Other](99-Other.html) ]**

## Bash

---

#### Reference

* ShellCheck
    
    https://www.shellcheck.net/  

* Advance Bash scripting
    
    https://tldp.org/LDP/abs/html/index.html  


#### Args

* Check number of arguments
    
    https://stackoverflow.com/questions/18568706/  
    
    ```
    if [[ $# != 1 ]]; then
        echo "Illegal number of parameters"
        exit 1
    fi
    ```

* Parsing args
    
    https://stackoverflow.com/questions/192249/  

    ```
    #!/usr/bin/bash

    DEV=0

    while (($#)); do
    case "$1" in
        -dev)
        DEV=1
        ;;
        *)
        DEV=0
        ;;
    esac
    shift
    done

    if [[ $DEV == 1 ]]; then
        echo ok
    fi
    ```


#### Directories

* Script directory
    
    https://stackoverflow.com/questions/59895/  
    
    `BASEDIR="$(dirname -- "$(readlink -f -- "$0";)")"`
    
    `BASEDIR="$( cd -- "$( dirname -- "${BASH_SOURCE[0]}" )" &> /dev/null && pwd )"`

* Parse sub directories

    ```
    #!/usr/bin/bash

    for dir in $PWD/*; do
        if [[ -d $dir ]]; then
            echo $dir
        fi
    done
    ```


#### Files

* Test file extension
    
    https://stackoverflow.com/questions/21425006/  
    
    ```
    #!/bin/bash

    inpath="file.html"

    if [[ "${inpath: -5}" == ".html" ]];then
        echo ok
    fi
    ```

* Change file extension
    
    https://stackoverflow.com/questions/1224766/  

    ```
    inpath=file.md
    outpath=${inpath%.md}.html
    ```
* Heredoc
    
    https://linuxize.com/post/bash-heredoc/  
    
    ```
    dest=~/test.txt
    sudo tee $dest > /dev/null << EOF
    bla
    ble
    blie
    EOF
    ```

* Output to file and stdout
    
    https://stackoverflow.com/questions/418896/  
    
    ```
    program [arguments...] 2>&1 | tee -a "$outfile"
    ```


#### Misc

* Write functions
    
    https://linuxize.com/post/bash-functions/  

* Checking sudo
    
    https://stackoverflow.com/questions/42875809/  
    
    ```
    if [[ "$EUID" = 0 ]]; then
        echo "(1) already root"
    else
        sudo -k # make sure to ask for password on next sudo
        if sudo true; then
            echo "(2) correct password"
        else
            echo "(3) wrong password"
            exit 1
        fi
    fi
    ```

