# x86 Salvation

## Support information for the x86 (32-bit) architecture

32-bit computer architecture is increasingly becoming the dinosaur of the PC world these days, especially in the Linux zone.

Considering that almost every other linux distro and every major software vendor are announcing dropping support for x86, a day might soon come when words like `i386`, `x86` and `32-bit` will fade away from people's memory seeing how fast things move in the IT world. On that day, this list could be helpful to someone wanting to use an old x86 PC or laptop or VM for whatever reasons.

## Linux and BSD

- [Debian](https://docs.python.org/) - Thankfully, Debian is one of the few distros who has maintained x86 support as of now (2019) though we can't say for how long that will hold.
- [Ubuntu](https://ubuntu.com) - Ubuntu has stopped support for x86 since [16.04 LTS](http://releases.ubuntu.com/16.04.6/) which is the last downloadable distro with x86 support. However, you can use lighter variants like [lubuntu](https://lubuntu.net/) and [xubuntu](https://xubuntu.org/) who still support x86 (as of 2019) but its uncertain how long they'll do that.
- [Linux Mint](https://linuxmint.com/download.php) - In a [recent blog post](https://blog.linuxmint.com/?p=3766), Linux Mint has announced that since the upstream (Ubuntu) has dropped support for 64-bit, Linux Mint will be forced to do the same with future versions of 20.x. 19.x is the last 32-bit release and will be supported until 2023.
- [Fedora](https://getfedora.org/) - Thankfully, Fedora has retained support for [32-bit builds](https://download.fedoraproject.org/pub/fedora-secondary/releases/30/Workstation/i386/) as of now.
- [Gentoo](https://www.gentoo.org/) - Gentoo is a difficult distribution for the average linux user to master but thankfully, [they do support 32-bit arch](https://www.gentoo.org/downloads/) as of now.
- [FreeBSD](https://www.freebsd.org/) - FreeBSD still has [full support for i386](https://www.freebsd.org/platforms/index.html) as of now.

## Software

### Languages, Interpreters and Runtimes

- Node.js: Node has [officially stopped supporting x86 since 10.x LTS version](https://github.com/nodesource/distributions/blob/master/README.md#deb). The last Node LTS you can use on an x86 is 8.x using the instructions on the linked page. However, they have plans to revive i386 builds [unofficially as mentioned here](https://unofficial-builds.nodejs.org/).
- Java: Official JDK (Oracle) has stopped x86 support since Java 11. The last Oracle x86 JDK you can install is [Java 8](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html). The same is with Amazon Corretto and others, almost every major Java vendor has dropped support for x86 since the 8.x branch.
- Python: Python has (thankfully!) maintained support for x86 as of now (v3.74) for [windows and mac](https://www.python.org/downloads/release/python-374/), and their source tar files should trivially compile to i386 on linux as major distros like debian are shipping i386 versions of it.
- PHP: PHP has [maintained support for x86](https://windows.php.net/download#php-7.3) for windows as of now. Building PHP using C is also usually trivial for x86 on linux.

### Databases

- MongoDB: MongoDB has absolutely stopped support for x86 arch through repos. The only way to install mongodb on a linux machine is to extract the [latest supported tar build](https://fastdl.mongodb.org/linux/mongodb-linux-i686-3.0.6.tgz) and installing the binaries yourself. Based on my testing, it works on ubuntu trusty.
- MySQL - MySQL Server (GPL Community Edition) has [maintained support for x86](https://dev.mysql.com/downloads/windows/installer/8.0.html) for windows as of now. It should also be trivially available on i386 versions of various linux distros.


*This list is evolving as new information about i386 systems comes up, feel free to contribute!*


*Links*

- **MongoDB**
- <https://stackoverflow.com/questions/43960037/is-it-possible-to-install-mongodb-on-32-bit-ubuntu-16-04-lts>
- <https://askubuntu.com/questions/772181/how-can-i-install-mongodb-on-32-bit-ubuntu>
- **Node.js**
- [Discussion surrounding Node.js decision to drop 32-bit builds](https://github.com/nodejs/build/issues/885)
- <https://nodejs.org/en/download/package-manager/>
- <https://github.com/nodejs/help/issues/1384>
- <https://github.com/nodesource/distributions/blob/master/README.md>
- **Node.js (Unofficial i386 builds)**
- <https://unofficial-builds.nodejs.org/download/>
- <https://github.com/nodejs/unofficial-builds/>
- **Java**
- <https://stackoverflow.com/questions/55808777/amazon-corretto-11-32-bits>
- **Python**
- <https://www.python.org/downloads/release/python-374/>