# Medjed Assembly

This repository contains the CAD files and assembly of the [MEDJED Maskless lithography system](https://github.com/openMLA/Medjed). CAD files are generated with FreeCAD.

Note that the [Wiki](https://github.com/openMLA/Medjed/wiki) and [Discussions](https://github.com/openMLA/Medjed/discussions) for the project are located in the main Medjed repository.

### Organisation

This repository should generally be obtained as a submodule of the main Medjed repository. That other repository will also have code and PCB designs for the project. 

The binary files are managed through [git-annex](https://git-annex.branchable.com/). When you first clone this repository these files will not have been downloaded, so you will see the history of the files, but not be able to open them.

To download these files, simply run (in git bash, or some terminal with git support)

``` shell
git-annex get .
```

Which should download all the files. If you only want a subset of the files, you can also run e.g. ` git annex get /optics/*.FCStd`. The files are stored on a [google cloud storage special remote](https://gist.github.com/NemoAndrea/86f93e55a579ad4e2c7e8fea4603c1c2).

### Freecad Configuration

The project uses two FreeCAD plugins, and it is recommended you install these before working with the files. You can easily install these with the built-in plugin manager of FreeCAD.

1. [Assembly 4 workbench 🏗](https://github.com/Zolko-123/FreeCAD_Assembly4)
2. [Optics workbench 🔍](https://github.com/chbergmann/OpticsWorkbench)
3. [KicadStepUp ⚡](https://github.com/easyw/kicadStepUpMod)