# Kali-Linux
This repository consists of a wiki about a brief introduction to Kali Linux OS, due to an Operating Systems class assignment

Welcome to the Kali-Linux wiki!

## History
It was developed by Mati Aharoni and Devon Kearns of Offensive Security through the rewrite of BackTrack, which was their previous security testing Linux distribution based on Knoppix.

Putting in everything into a timeline, the Kali Linux project began quietly in 2012, as a willingness to replace the BackTrack Linux project, which was manually maintained, with something that could become a genuine Debian derivative characterized by its quality, stability, and completeness in terms of infrastructure and packaging techniques. After one year of development, in March 2013, the first release (version 1.0) happened and was based on Debian 7 “Wheezy”, Debian’s stable distribution at the time.

## So what is it?
Is a Debian-based Linux distribution aimed at advanced Penetration Testing and Security Auditing, that is, kali allows its user to use several tools geared towards information security tasks as Penetration Testing, Security research, Computer Forensics, and Reverse Engineering.

## Installation 

Firstly, the ISO has to be downloaded, this can be done in the Kali Linux Official page https://www.kali.org/downloads/

![](https://i.imgur.com/LnjCJjz.png)

After booting the image the following screen will be displayed, where the install option will be selected

![](https://i.imgur.com/nmPqYPk.png)

The next step is to select the keyboard map and its language

![](https://i.imgur.com/u4AYGOM.png)

![](https://i.imgur.com/NTfO0G0.png)

Then a domain name must be assigned

![](https://i.imgur.com/kQkWR4G.png)

The root user password is asked

![](https://i.imgur.com/r1iUMdY.png)

Lastly, the disk unit in which the OS will be installed must be specified

![](https://i.imgur.com/BOxON9r.png)

## Package manager
Since Kali Linux is based on Debian then its default package manager is dpkg, tool in charge of installing, removing, and providing information about packages through the use of APT (Advanced Package Tool). In the following image it will be presented an example of how to update the package lits in Kali Linux:

![](https://i.imgur.com/8b4i3ue.png)

## Desktop environment
The default desktop environment used by Kali Linux is GNOME, in charge of launching applications, switching between windows, provide a user-friendly suite and an easy-to-use desktop.

![](https://i.imgur.com/x7PGnBg.png)
## Kernel version
The latest version of Kali Linux kernel is 4.19.13 used in Kali 2019.1 release. Kali Linux is a rolling release distribution, hence its upgrades are frequently released, maybe not with a fixed timeframe but every few months there is a new OS image to use as seen in their latest releases:

![](https://i.imgur.com/kJqr5EY.png)

## Important releases

### Kali 2.0

In this release, Kali Linux became a rolling release distribution, offering support to a wide variety of desktop environments like KDE, GNOME3, Xfce, MATE, e17, lxde, and i3wm, but took the initiative to migrate to the use of GNOME3, that after a few modifications became the desktop environment by default.

### Kali 2018.2

Updated the kernel to Linux 4.15 and provided better support for AMD GPUs and the encryption of virtual machines so that even the hypervisor could not access it. Included patches for the Meltdown and Specter vulnerabilities, and extended support for ARM devices such as Raspberry Pi, Chromebooks, Odroids.

## Advantages / Disadvantages

There are many things that Kali Linux OS bring to us, this is a few of them:

* Access to multiple security tools and penetration tests.
* Management of Secure Packages.
* Support the standard file system hierarchy.
* ARM Systems Support


There are also a few disadvantages like:

* There is only one user mode, root.
* Application compatibility problems between distributions.
* Hardware compatibility problems.

## References

https://itsfoss.com/kali-linux-review/

https://www.kali.org/kali-linux-releases/

https://en.wikipedia.org/wiki/Kali_Linux

https://docs.kali.org/introduction/what-is-kali-linux


