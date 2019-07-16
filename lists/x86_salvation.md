# i386 Salvation

## Support information for the i386 architecture

`i386` architecture is increasingly becoming the dinosaur of the PC world these days, especially in the Linux world.

Considering that almost every other linux distro and every major software vendor are announcing dropping support for i386, a day might soon come when `i386` (and `x86` and `32-bit`) words might fade from people's memory seeing how fast things move in the IT world! On that day, this list could be helpful to someone wanting to use an old i386 PC or laptop or VM for whatever reasons.

## Linux

- [Debian](https://docs.python.org/) - Thankfully, Debian is one of the few distros who has maintained x86 support as of now (2019) though we can't say for how long that will hold.
- [Ubuntu](https://ubuntu.com) - Ubuntu has stopped support for x86 since [16.04 LTS](http://releases.ubuntu.com/16.04.6/) which is the last downloadable distro with x86 support. However, you can use lighter variants like [lubuntu](https://lubuntu.net/) and [xubuntu](https://xubuntu.org/) who still support x86 (as of 2019) but its uncertain how long they'll do that.
- [Linux Mint](https://linuxmint.com/download.php) - Thankfully, Linux Mint has retained support for 32-bit builds as of now.
- [Fedora](https://getfedora.org/) - Thankfully, Fedora has retained support for [32-bit builds](https://download.fedoraproject.org/pub/fedora-secondary/releases/30/Workstation/i386/) as of now.

## Software

- MongoDB: MongoDB has absolutely stopped support for x86 arch through repos. The only way to install mongodb on a linux machine is to extract the [latest supported tar build](https://fastdl.mongodb.org/linux/mongodb-linux-i686-3.0.6.tgz) and installing the binaries yourself. Based on my testing, it works on ubuntu trusty.
- Node.js: Node has [absolutely stopped supporting x86 since 10.x LTS version](https://github.com/nodesource/distributions/blob/master/README.md). The last Node LTS you can use on an x86 is 8.x using the instructions on the linked page.
- Java: Official JDK (Oracle) has stopped x86 support since Java 11. The last Oracle x86 JDK you can install is [Java 8](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html). The same is with Amazon Corretto and others, almost every major Java vendor has dropped support for x86 since the 8.x branch.
- Python: Python has (thankfully!) maintained support for x86 as of now (v3.74) for [windows and mac](https://www.python.org/downloads/release/python-374/), and their source tar-balls should trivially compile to i386 as major distros like debian are shipping i386 versions of it.

*This list is evolving as new information about i386 systems comes up, feel free to contribute!*


*References*
- **MongoDB**
- <https://stackoverflow.com/questions/43960037/is-it-possible-to-install-mongodb-on-32-bit-ubuntu-16-04-lts>
- <https://askubuntu.com/questions/772181/how-can-i-install-mongodb-on-32-bit-ubuntu>
- **Node.js**
- <https://nodejs.org/en/download/package-manager/>
- <https://github.com/nodejs/help/issues/1384>
- <https://github.com/nodesource/distributions/blob/master/README.md>
- **Java**
- <https://stackoverflow.com/questions/55808777/amazon-corretto-11-32-bits>
- **Python**
- <https://www.python.org/downloads/release/python-374/>