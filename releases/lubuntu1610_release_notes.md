# lubuntu 16.10 Release Notes

## New Features in Lubuntu 16.10
- **The switch to LXQt has been postponed.**
- We now ship with Linux Kernel 4.8.
- General bug fix release as we prepare for LXQt.
- LXDE components have been updated.
- The artwork has received an update. 

## Lubuntu Applications
- Based on the lightweight [LXDE desktop environment](http://lxde.org/).

- [PCManFM](http://wiki.lxde.org/en/PCManFM), a fast and lightweight file manager.

- [Openbox](http://openbox.org/), the fast and extensible, default windows-manager of LXDE.

- [LightDM](https://launchpad.net/lightdm), using the simple GTK greeter.
- Mozilla Firefox.

- For more detail, please see the [full list of applications](https://help.ubuntu.com/community/Lubuntu/Setup#Applications). 

## System Requirements

Lubuntu is a good operating system for many old computers, but not for all of them. Some computers have too little horsepower or memory. A rule of thumb is that the computer should not be more than 10 years old.

### Memory (RAM)

For advanced internet services like Google+, YouTube, Google Drive, and Facebook, your computer needs at least 1 GB of RAM.

For local programs like LibreOffice and simple browsing habits, your computer needs at least 512 MB of RAM.

### Processor (CPU)

The minimum specification for CPU is Pentium 4 or Pentium M or AMD K8. Older processors are too slow and the AMD K7 has problems with Flash video. 

## Upgrade

- To upgrade from Lubuntu 16.04 LTS, read our instructions for doing so. 

## Known Problems
### Common Infrastructure
For bugs affecting all flavors, please refer to the [Ubuntu release notes](https://wiki.ubuntu.com/YakketyYak/ReleaseNotes). 

### Lubuntu Applications
This is our list of known bugs affecting applications that Lubuntu uses but relies on others to maintain.

- gnumeric menu ->help ->about gnumeric -> license button, does not work. ([1516454](https://pad.lv/1516454)).

- Software properties gtk implies my cpu is unknown and not working. ([1444682](https://pad.lv/1444682)).

- Desktop file does not open ImageMagick from the menu ([1550210](https://pad.lv/1550210)).

- gparted does not recognize the iso9660 file system in cloned Ubuntu USB boot drives ([1622313](https://pad.lv/1622313)).

- sh: 1: /lib/libc.so.6: not found ([1473142](https://pad.lv/1473142)). (**fix pending**)

### Lubuntu-specific Bugs
These are maintained by the Lubuntu team. 
#### LXDE

- run dialog called from one desktop opens on the desktop with preferences dialog, regardless of which desktop is current ([1445818](https://pad.lv/1445818)).

- changing multiple desktop names only results in the first being changed. ([1522625](https://pad.lv/1522625)). 

#### Lubuntu Installer

- **All images require a DVD or USB. As a workaround, use the [server or netboot](https://help.ubuntu.com/community/Lubuntu/Alternate_ISO#CD_image) images.**

 - Lubuntu 16.10 slideshow still incorrectly showing Lubuntu Software Center ([1633148](https://pad.lv/1633148)).

 - GTK warning about "The :insensitive pseudo-class is deprecated. Use :disabled instead." in Lubuntu 16.10 installer output ([1633135](https://pad.lv/1633135)). 
 
 ## Support
- This release is supported for 9 months.

- [Contact us](https://wiki.ubuntu.com/Lubuntu/ContactUs). 
