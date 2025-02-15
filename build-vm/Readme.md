#Building the Jalangi VM:
###Instructions:
1. Download and install [Vagrant](https://www.vagrantup.com/) and [VirtualBox](https://www.virtualbox.org/).
2. Download this folder ("build-vm").
3. In a terminal, navigate to this folder and run the command "vagrant up".
4. Wait for several minutes as script runs. The VM's screen will pop-up midway through preparation, but don't use it until it's completely finished. Depending on your internet connection, it could take somewhere between 10 and 15 minutes, and it will reboot before it's done.

In this version, the script only creates an instance of Ubuntu 14.04 and installs Java 7. This script was modified slightly from the command line installation that the [official Jalangi Readme](https://github.com/SoftwareEngineeringToolDemos/FSE-2013-Jalangi/blob/master/README.md) provides.

###VM Credentials:

Username: vagrant

Password: vagrant


###Notes:

The base box used for the Vagrant script is [box-cutter/ubuntu1404-desktop](https://vagrantcloud.com/box-cutter/boxes/ubuntu1404-desktop).

You may need SSH for Vagrant to work. For Windows, you can use OpenSSH as part of [Cygwin](https://www.cygwin.com/).

Sources for certain commands used in the script:
* [Silenty installing Java](http://askubuntu.com/questions/190582/installing-java-automatically-with-silent-option).
* [Autostart programs](http://askubuntu.com/questions/48321/how-do-i-start-applications-automatically-on-login)
* [AutoLogin](https://help.ubuntu.com/community/AutoLogin)
