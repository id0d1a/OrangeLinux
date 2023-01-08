# OrangeLinux
OrangeLinux allows DEB/RPM packages to be installed on any linux distribution. 
Imagine being able to run distribution specific applications on any system. Well now you can with OrangeLinux


### Features

- Reads YUM repositories
- Reads APT repositories
- FakeYUM to run yum on non-RHEL based systems
- FakeAPT to run apt on non-debian based systems
- Custom OrangeLinux Repos Support
- Should work on non APT & non YUM systems. When installing applications files may get replaced.
- ConvertDEB to convert debian packages into OrangeLinux packages (OLP extension)
- ConvertRPM to convert RHEL packages into OrangeLinux packages (OLP extension)
- Fake Distribution naming
- Quick Install (Installs FakeYUM, FakeAPT, ConvertSystem, OrangeLinux Base System)

### What this contains

FakeYum - Replaces the yum package manager with ours, when installing fakeyum, all packages that yum knows about will be added. 
This will also be installable on any system that normally does not have the yum package manager.

FakeAPT - Replaces the apt package manager with ours, when installing fakeapt, all packages that apt knows about will be added.
This will also be installable on any system that normally does not have the apt package manager.

OrangeLinux Repo Creator - This allows users to create there own orangelinux repos and host there own packages.

ConvertDEB - Converts Debian packages into OrangeLinux packages

ConvertRPM - Converts RPM packages into OrangeLinux packages

FakeSystem - Temperary change the current distro into a fake distribution which allows any application to run.

OrangeLinux Base System - Our custom package manager commands.

### How to create a package?

Simply create either a RPM/DEB package then run our convert scripts
