# csl_styles
Repository for Citation Style Language (CSL) citation styles of use to me. 

The main source of included styles is the [open source Citation Style Language (CSL) project](http://citationstyles.org/):
- CSL's [github repo](https://github.com/citation-style-language) which is truncated to 1000 styles
- Extensive databse of many CSL styles in [zotero](https://www.zotero.org/styles) with search facility

### How to use
Symlink required style into the relevant project folder:

```
┌── ln(1) link, ln -- make links
│   ┌── Create a symbolic link.
│   │                         ┌── the optional path to the intended symlink
│   │                         │   if omitted, symlink is in . named as destination
│   │                         │   can use . or ~ or other relative paths
│   │                   ┌─────┴────────┐
ln -s /path/to/original /path/to/symlink
      └───────┬───────┘
              └── the path to the original file/folder
                  can use . or ~ or other relative paths
```

Ref: [How can I create a symbolic link in Terminal?](https://apple.stackexchange.com/a/115647)
