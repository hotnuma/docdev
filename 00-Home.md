<link href="style.css" rel="stylesheet"></link>

**[ Home | [Build](05-Build.html) | [Git](10-Git.html) | [Bash](15-Bash.html) | [Cpp](25-Cpp.html) | [Gtk](30-Gtk.html) | [Other](99-Other.html) ]**

## Docs Dev

---

#### References

* Freedesktop
    
    [freedesktop-desktop-entry](https://specifications.freedesktop.org/desktop-entry-spec/desktop-entry-spec-latest.html)  
    [freedesktop-icon-naming](https://specifications.freedesktop.org/icon-naming-spec/latest/ar01s04.html)  

* Markdown
    
    [markdown-here-cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet)  
    [markdownguide-basic-syntax](https://www.markdownguide.org/basic-syntax/)  
    [codecademy-markdown-tables](https://www.codecademy.com/resources/docs/markdown/tables)  
    [writing-on-github](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)  


#### Patches

* patch
    
    try : `patch -p 1 --dry-run -i '../dir/my_file.patch'`
    
    do  : `patch -p 1 -i '../dir/my_file.patch'`


#### Code Formatting

* astyle
    
    One file : `astyle -n --style=allman thunar-window.c`

    Recursive : `astyle -nr --style=allman "test/*.h" "test/*.c"`

* clang-format
    
    https://clang.llvm.org/docs/ClangFormatStyleOptions.html  
    
    dump config : `clang-format -style=llvm -dump-config > _clang-format`  
    in current dir : `clang-format -i -style=WebKit *.c *.h`  
    
* Other
    
    [awesome-code-formatters](https://github.com/rishirdua/awesome-code-formatters)  
    [uncrustify](https://uncrustify.sourceforge.net/)  
    [clang-format](https://clang.llvm.org/docs/ClangFormat.html)  
    [gnu-indent](https://www.gnu.org/software/indent/)  


