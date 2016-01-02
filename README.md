# freecad-git-arch
FreeCAD-0.16-pre PKGBUILD with patch for archlinux

I had problems with FreeCAD.getHomePath() pointing to /usr instead of /usr/share/freecad. The original freecad.desktop also did not work for me, so I edited this, too. For FreeCAD, I found some patch solutions and created a pkgbuild + patch for FreeCAD which works for me (January 02, 2016). Take care though: The patch will probably stop working some day due to changes in FreeCAD (https://github.com/FreeCAD/FreeCAD). As I use FreeCAD constantly, I will try keeping this up to date if the PKGBUILD fails some day.

This package is based on the freecad-git AUR package which can be found here:
https://aur.archlinux.org/packages/freecad-git

As usual, this software comes with absoulutely no warranty, use this on your own risk.
