# pifactory
Test scripts to build Raspbery Pi images using PDK

Scripts included:
pifactory - handles distro building
pikernel - compiles kernel and packages as dpkg for inclusion in distro
pifirmware - packages non-free firmware as dpkg for inclusion in distro

Setup:
```
git clone https://github.com/64studio/pifactory
```

todo list:
* Debianize as part of PDK source package
* Integrate into PDK