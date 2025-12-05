SilvioLinux-OpenBox-Obmenu-Generator
==========================================

A fast pipe/static menu generator for the Openbox Window Manager, with support for icons.

![obmenu-generator]

---

```
usage: obmenu-generator [options]

menu:
    -p         : generate a dynamic menu (pipe)
    -s         : generate a static menu
    -i         : include icons
    -m <id>    : menu id (default: 'root-menu')
    -t <label> : menu label text (default: 'Applications')

misc:
    -u         : update the config file
    -d         : regenerate the cache file
    -c         : reconfigure openbox automatically
    -R         : reconfigure openbox and exit
    -S <file>  : absolute path to the schema.pl file
    -C <file>  : absolute path to the config.pl file
    -o <file>  : absolute path to the menu.xml file

info:
    -h         : print this message and exit
    -v         : print version and exit

examples:
        obmenu-generator -p -i     # dynamic menu with icons
        obmenu-generator -s -c     # static menu without icons
```

* <b>Config file:</b> `~/.config/obmenu-generator/config.pl`
* <b>Schema file:</b> `~/.config/obmenu-generator/schema.pl`

---

Installation: [INSTALL.md](INSTALL.md)
