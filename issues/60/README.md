# Using Fedora Server to build a minimal desktop

## Original proposal

Originated by Neil Connoly @nekon. 

Starting with a minimial server install is akin to a base Arch install.

Starting with a Workstation install is akin to a Manjaro install. 

An article detailing similar customisations for Fedora would be beneficial for Arch refugees trying to re-create their setup on Fedora.
It is also beneficial for existing Fedora users that love the tools available but desire the ability to customize their environment.
In no way should this article be considered an attack on Arch or an attempt to undermine the distro or it's community of users.

## Additional proposal

A common criticism of GUI desktops is that the user often has to adapt their workflow to fit the environment.
Another reason for taking this route is for purism; to only install the minimal amount of packages to achieve the desired functionalities.
This also has an additional benefit in so far as it can reduce the likelihood of package conflicts.
Many Linux distros have gone to great lengths to emulate Windows in order to ease the transition.
Whilst this is admirable in many respects one downside is that 

## Additional commentary

### Full disclosure

I am also an Arch refugee. 
I am also a Mint refugee. 
And a Raspbian refugee. 
And a Windows refugee. 
No axe grinding here. 
Any \*nix based distro is a fine distro.

## Personal journey

I've always had an interest in computers since I was child and over the years that interest has increased. 
Coming from a business background computers meant Windows. 
I started to tinker with Excel macros to automate some repetitive tasks. 
I kept adding features until one day it all broke and I was left staring at the BSOD. 
I knew behind the scenes of the macros Windows was autogenerating my VBA scripts. 
I also knew this process added in some code that wasn't strictly necessary and could be eliminated. 
That is when I moved away from macros to VBA. That solved that problem. 

What else could I do with my new found powers? 
More new features. 
Cue BSOD. 


Raspbian on RPi
 
 
- Mint Cinnamon dual-boot with Windows 7
- Mint Cinnamon
- Arch
- Fedora/CentOS

I switched to Fedora and CentOS as daily drivers for a simple reason. I have  

When I recently configured a QEMU/KVM/Libvirt setup on Fedora 35 I installed 3 VM's in the following order;

1) Fedora 35 Server minimal
2) Fedora 35 Workstation
3) Arch

## Comparison

A recent poll conducted on Reddit sub r/linuxmasterrace entitled "Panic! at the Distro" eventually pitted Arch against Fedora in the Grand Final.

Arch came out on top but there is undoubtedly a lot of love for Fedora in the Linux community.

### Arch Linux

Due to the minimal nature of Arch a degree post-installation setup is often required, subject to the required use case of course.

This barebones installation method, in combination with a more permissive licensing model and the AUR, fostered a DIY customization culture within the Arch community which is second to none in the wider Linux community.

The general consensus of Arch is that it is considered a bleeding edge distro. 
As a result it is unusual to find Arch servers in production environments where stability and security are the order of the day. 
On the other hand, this is fertile ground for bespoke desktop environments, tailored to the users specific requirements. 
Your system, your way.

Another note-worthy feature of Arch is of course, the Arch Wiki. 
The breadth and depth of coverage is unique. 
Users of other distros regularly consult it with a view to sourcing solutions to problems on their systems.

A number of popular distros have emerged that are derived from Arch but eschew the barebones approach. 
They provide the user with an opinionated, eye-catching environment but still afford the luxury of tweaking settings and packages. 
This also overcomes the widely held view that Arch is "difficult" or "complicated". 
You can get a system up and running quickly and start working immediately. 
The customization can then proceed alongside a productive workflow.

### Fedora Linux

In contrast to Arch, RHEL is a complete family of distros for any number of uses. 
Given it's origins in production environments it has a more sober, less exuberant image. 
If both distros were educational qualifications, Arch is a BA wheras RHEL is a BSc. 
Arch is soaring architecture. 
RHEL is precision engineering.

The general consensus of Fedora is that it is leading edge. 
The range of options available under one umbrella organisation means you can find instances in a range of environments from SBC's and desktops at one end through to data centres at the other.

A reputation for quiet efficiency seems to be a consistent theme in user forums. 
For those users that want well-engineered tools, immediately available with an attractive interface, Fedora is an obvious choice. 
"Vorsprung durch technik", as they say in Germany.

The flagship desktop is GNOME however there are a range of alternatives from the eye-popping visuals of KDE Plasma through to Spartan, lightweight desktops like XFCE. 
All these GUI desktops are available as group packages via dnf. 
Furthermore, the "Basic Desktop" group package contains a number of tiling window managers like i3, Awesome and my personal favourite, qtile which is a scriptable, python based WM.

### Conclusion




