## Common  Setup Instructions
#### Softwares:  Virtualbox, Vagrant, Git, Atom , ConEMU
====================


### Systems Preparation

To setup the lab, as participants, we would create Virtual Machines with VirtualBox and setup the learning environment. Vagrant is a tool which allows us to build, configure and setup portable virtual machines automatically, and it works with multitude of hypervisors, Virtualbox included. We would also need a sophisticated  editor with chef plugin, which would help us write code fast, with auto completion and syntax highlighting features etc. Thats where Atom comes in handy.  

On windows systems, utilities such as ssh do not come installed by default. To install a bash shell and create a remote terminal, Git and ConEmu are effective tools.


#### Enabling Virtualization from BIOS

In order to run 64bit VMs, systems need to be enabled with hardware virtualization extensions. On a Mac OSX, this is typically enabled by default. However, on many Windows Laptops/Desktops, VT-x needs to be manually enabled.

[Enable Hardware Virtualization Technology(VT -x) from BIOS](https://docs.fedoraproject.org/en-US/Fedora/13/html/Virtualization_Guide/sect-Virtualization-Troubleshooting-Enabling_Intel_VT_and_AMD_V_virtualization_hardware_extensions_in_BIOS.html)

These instructions different from system to system, bases on the BIOS provided with your laptop/desktop. For a lot of systems, Virtualization options are found in **Security** tab.

#### Installing Required Softwares - Common



| Software  | Version Tested     |
| :------------- | :------------- |
| Virtualbox       | 5.0.10      |
| Vagrant | x |
| Atom | x  | 
| Chef Development Kit (ChefDK) | x |
| Git for Windows ( on windows only) | x |
| ConEmu ( on windows only) | x |

* Install [Oracle VirtualBox](https://www.virtualbox.org/wiki/Downloads). At the
time of writing this document, the latest tested version of VirtualBox is 5.0.10
* Install [Vagrant](http://www.vagrantup.com/downloads). At the time of
writing, the latest version of Vagrant is 1.8.1
* Install [Atom](https://atom.io) editor from

#### Installing Required Softwares - Windows Specific

In addition to the common softwares above, windows systems also need the following softwares.

* Download and install  [GIT for windows](https://msysgit.googlecode.com/files/Git-1.9.0-preview20140217.exe)
* ConEmu is a terminal emulator for windows, supports multiple tabs, and can work with git bash to open bash terminals. Download and install it from [here]( http://www.fosshub.com/ConEmu.html/ConEmuSetup.150813g.exe)
