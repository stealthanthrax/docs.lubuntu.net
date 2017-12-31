# lubuntu 10.10 Release Notes

## What is Lubuntu

Lubuntu is an Ubuntu derivated using the LXDE desktop. It’s designed to be a lightweight and easy-to-use desktop environment. Lubuntu is actually not part of the Ubuntu family, and not build with the current Ubuntu infrastructure. This release is considered as a « stable beta », a result that could be a final and stable release if we was included in the Ubuntu family.


### Features

* Based on the lightweight LXDE desktop environment.
* Pcmanfm 0.9.7, a fast and lightweight files manager using gio/gvfs.
* Lxdm, a lightweight GTK display manager.
* Chromium, the open-source version of Google Chrome.
* … and, of course, based on Ubuntu 10.10


### Improvements since Lubuntu 10.04

#### Applications by default
Programs installed by default have been updated

* Added
	* Update-notifier, to get notification for available updates.
	* Xpad, to create quick notes (similar to Tomboy).
	* Ace-of-penguins, to provide some games

* Removed
	* Parcellite, which is not maintained upstream, is less useful since most of copy/paste bugs was gone with pcmanfm 0.9.X
	* Pyneighborhood was replaced by gvfs support of pcmanfm.

* Changes
	* LXtask replace Xfce4-taskmanager for tasks monitoring.
	* Evince is now used for reading PDF, ePDFview have some serious memory leaks.
	* New theme

#### Installer slideshow
* New slideshow is available during the installation, to describe Lubuntu and its features.

#### Indicators supports
* Lxpanel now support Ubuntu indicators applets. This feature is turn off by default, but you can activate it by adding the “Indicators applet”.

#### New extras packages
* A new meta-package (lubuntu-core) is available to install only core packages of Lubuntu.
* A new meta-package (lubuntu-restricted-extras) is available to install restricted packages for Lubuntu (such as flash, java and extra codecs for Chromium)

#### LXDE updates
* LXDE is now HAL-free. Lubuntu still depends on HAL for CD-burner, but by removing it, you can obtain a HAL-free system.
* New lxappareance from LXDE git (without Openbox integration)
* And the usual updates of LXDE and Ubuntu packages included in Lubuntu.
