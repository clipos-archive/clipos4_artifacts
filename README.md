# CLIP OS 4 Artifacts

Set of raw archives tied to CLIP OS 4.

:warning: This repository is managed with Git LFS.

Ensure to have Git LFS installed on your system to properly fetch the files which are not directly stored within this Git repository.
To download these artifacts and all the other necessary files to build CLIP OS 4, please follow [these instructions](https://github.com/clipos-archive/clipos4_manifest/blob/master/README.md).

## CLIP OS 4 SDK

[This archive](https://gitlab.com/CLIPOS-Archive/clipos4_artifacts/raw/master/clip-sdk_2019-06-06.tar.xz) can be used as the rootfs of a (x86-64) LXC container with an appropriate [configuration](https://github.com/clipos-archive/src_platform_clip-devutils/tree/master/share/lxc).
The necessary steps to set up this SDK can be found in the [development documentation](https://github.com/clipos-archive/clipos4_doc/blob/master/developpeur/1103_Environnement_de_Developpement_2.3.pdf).
You can then follow the [packaging documentation](https://github.com/clipos-archive/clipos4_doc/blob/master/developpeur/4001_Guide_de_Creation_de_Paquetage_1.3.pdf) to build CLIP OS 4.
