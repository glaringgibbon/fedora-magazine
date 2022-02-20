# General approach

With the sheer number of packages available and the possible use cases for a desktop it is impossible to write an article that covers every eventuality.
This article works through the general process and notes convenient jump off points that could be taken.
Working through the following Arch wiki sections as a guide;

- https://wiki.archlinux.org/title/General_recommendations
- https://wiki.archlinux.org/title/List_of_applications

## Post-install from minimal

Assumed installation is complete already. 
There is a major difference here between the two distros.
You will have arrived at this point much faster than an Arch install.
This isn't criticism, just a fact.
You'll also have covered most of the next section too.

## System administration

Assuming all users were included during install there is nothing further to do here except give some consideration to systemd.

### Systemd

TODO Very brief systemd/init target discussion.

### Package management

Open dnf.conf with vim and add text at the bottom

```
$ sudo vim /etc/dnf/dnf.conf
fastestmirror=1
max_parallel_downloads=10
deltarpm=True
defaultyes=True
```

## Group packages

Fedora repos contain group packages to simplify the installation of related packages. 
Desktop environments are a collection of different packages not a monolithic  

```
dnf group list
```

- KDE Plasma Workspaces
- Xfce Desktop
- LXDE Desktop
- LXQt Desktop
- Cinnamon Desktop
- MATE Desktop
- Sugar Desktop Environment
- Deepin Desktop
- i3 desktop
- Basic Desktop
- Window Managers
- Deepin Desktop Environment
- GNOME
- KDE

# Other

- Fedora Custom Operating System
- Sound and Video
