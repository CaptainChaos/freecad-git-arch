# freecad-git-arch
FreeCAD-0.16-pre PKGBUILD with patch for archlinux

I had problems with FreeCAD.getHomePath() pointing to /usr instead of /usr/share/freecad. I found some solutions and created a pkgbuild + patch for FreeCAD which work for me (January 02, 2016), although the patch will probably stop working some day due to changes in https://github.com/FreeCAD/FreeCAD.

This package is based on the freecad-git AUR package which can be found here:
https://aur.archlinux.org/packages/freecad-git

As usual, this software comes with absoulutely no warranty, use this on your own risk.
