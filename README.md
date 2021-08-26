# Iris Linux

I am proud to announce the very first public release of Iris Linux. There is some stuff you need to know beforehand...

First off, there is two live CDs available. "iris-linux-0.1-5.10-xfce-x86_64" includes a fully working version of xfce4 (desktop environment), while "iris-linux-0.1-5.10-console-x86_64" just includes some basic utilities.

Also, the "xfce" live CD uses a version of the Linux kernel from LFS EXTON, instead of the one built for Iris Linux (that one is still included inside the squashfs filesystem under /boot, though). This is because I couldn't get our own kernel working on a live CD AND with XOrg support (what is used for xfce4). Please ignore errors from the kernel on ANY live CD, since they are expected to pop up.

Furthermore, the live environment isn't completely finished yet. For instance, Iris Linux can't install itself onto a hard drive (you can do it yourself using the squashfs filesystem, but it's for advanced users and no tutorial will be provided as of now), and it mostly doesn't come with networking and audio support out of the box (they are configurable, it's just as I have it personally configured on my PC, where I performed all tests at). All of this doesn't mean the live CDs aren't usable; if you can't get networking/sound working, I installed some cool stuff for you to check out (they probably won't be included in future updates).

Apart from that, Iris Linux uses pacman as its package manager, and has Arch Linux's repositories by default. However, it is not as simple to use as usual. Please check /how-to-use-pacman.txt inside the root filesystem to learn more, and don't hesitate to ask if you run into any issues.

Lastly, to login you either got to use the root user or the iris user. The passwords are the same as the usernames in both cases.

# What does all of that mumbo-jumbo on the .iso file mean?

Example: iris-linux-0.1-5.10-xfce-x86_64

iris-linux = distro name

0.1 = distro version

5.10 = kernel version

xfce = distro flavor

x86_64 = distro architecture

# Screenshots

![image](https://user-images.githubusercontent.com/13150712/131042982-4eae0fbb-5547-4ad7-a8e5-371ef824e44f.png)
![image](https://user-images.githubusercontent.com/13150712/131042956-b8a9db7b-719f-4f27-b566-daf14d457eef.png)
![image](https://user-images.githubusercontent.com/13150712/131043046-4ac64585-4061-4ae9-8705-993ca7de267b.png)
![image](https://user-images.githubusercontent.com/13150712/131043054-62d95197-1689-40b5-bd83-2da74baf48cb.png)
![image](https://user-images.githubusercontent.com/13150712/131043058-527f6757-6741-4145-a2ac-71dc9c2a9fb7.png)

# Special thanks

Linux from Scratch: https://www.linuxfromscratch.org/lfs/

Beyond Linux from Scratch: https://www.linuxfromscratch.org/blfs/

Arch Linux: https://archlinux.org/

Exton Linux: https://linux.exton.net/

Live Linux Kit: https://www.linux-live.org/
