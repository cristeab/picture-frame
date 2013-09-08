Frame Picture
================================

This KDE Plasmoid is used for showing pictures and has been extracted from [KDE Plasma Addons]
(git://anongit.kde.org/kdeplasma-addons) and packaged for [Plasma Active](http://plasma-active.org/).

Preparation for building on Mer OBS
-------------------------------------------
In order to generate *.spec file from *.yaml file you need to install [Spectacle Toolset]
(https://github.com/mer-tools/spectacle), then use the following command (from the main folder of the project):

    specify picture-frame.yaml

From the same folder, generate the source archive with:    
    git archive --format=tar --prefix=picture-frame-1.0/ HEAD | bzip2 > picture-frame-1.0.tar.bz2

The following files must be uploaded into a Mer OBS package:
- picture-frame.yaml
- picture-frame.spec
- picture-frame-1.0.tar.bz2
