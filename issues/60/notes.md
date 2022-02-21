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

To learn more about dnf see [here](https://dnf.readthedocs.io/en/latest/)

Open dnf.conf for editing

```
$ sudoedit /etc/dnf/dnf.conf
```

Add this text at the bottom

```
ip_resolve=4
max_parallel_downloads=20
defaultyes=True
```

Or echo into file with this, repeating the command for the other items

```

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
