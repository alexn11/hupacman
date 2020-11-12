A script that wraps pacman inside an easier to remember version of pacman. This definitively cannot do everything but it can do most of the common tasks.

Examples:
```
# install a new package from the mirrors
hupacman install linux
# upgrade the system
hupacman upgrade
# show package version
hupcman version linux
# list all the actions
hupacman -h
```

The latter should print something like:
```
Options: --help (-h)
Actions:
 check-if-installed  PACKAGE_NAME
 cleanup-cache  NB_VERSIONS_TO_KEEP
 downgrade  PACKAGE_NAME
 download-system-upgrade 
 find-installed-packages  PACKAGE_REGEXP
 install  PACKAGE_NAME
 install-aur  PACKAGE_NAME
 install-file  FILE_PATH
 list-cached-versions  PACKAGE_NAME
 list-explicitely-installed-packages 
 list-installed-package-versions 
 list-installed-packages 
 list-orphan-dependencies 
 list-outofdate-packages 
 show-dependencies  PACKAGE_NAME
 show-dependencies-tree  PACKAGE_NAME
 show-info  PACKAGE_NAME
 show-installed-version  PACKAGE_NAME
 show-journal 
 show-journal-last-lines  NB_LINES
 show-what-depends-on  PACKAGE_NAME
 show-which-package-provides  FILE_PATH
 uninstall  PACKAGE_NAME
 uninstall-and-remove-conf  PACKAGE_NAME
 upgrade-system 

  Alternative action names:
     check-if-installed : installed
     cleanup-cache : cache, clean-cache, clean-up-cache, clear-cache
     download-system-upgrade : download-upgrade
     find-installed-packages : find
     install-aur : aur, aur-install
     list-explicitely-installed-packages : explicit, list-explicit
     list-orphan-dependencies : list-orphans, orphans
     show-dependencies : dependencies, depends
     show-dependencies-tree : tree
     show-info : info
     show-installed-version : version
     show-journal : journal, log
     show-journal-last-lines : journal-tail, log-tail
     show-what-depends-on : depends-on, required-by
     uninstall : remove
     uninstall-and-remove-conf : full-remove, full-uninstall
     upgrade-system : upgrade
```

Warning: I take absolutely no responsability whatsoever if anything bad (or good, or neutral) happens during or following the use/download/copy/etc. of this script, or because of anything in relation to this script.





