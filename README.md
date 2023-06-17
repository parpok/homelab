# homelab

This repository is for my Homelab. Mostly stuff like config files for services I decided to set up

# My Homelabs specs

```
[jenot@sayu ~]$ neofetch
             .',;::::;,'.                jenot@sayu 
         .';:cccccccccccc:;,.            ---------- 
      .;cccccccccccccccccccccc;.         OS: Fedora Linux 38 (Server Edition) x86_64 
    .:cccccccccccccccccccccccccc:.       Host: H110M-S2H 
  .;ccccccccccccc;.:dddl:.;ccccccc;.     Kernel: 6.3.5-200.fc38.x86_64 
 .:ccccccccccccc;OWMKOOXMWd;ccccccc:.    Uptime: 24 mins 
.:ccccccccccccc;KMMc;cc;xMMc:ccccccc:.   Packages: 1092 (rpm) 
,cccccccccccccc;MMM.;cc;;WW::cccccccc,   Shell: bash 5.2.15 
:cccccccccccccc;MMM.;cccccccccccccccc:   Terminal: /dev/pts/1 
:ccccccc;oxOOOo;MMM0OOk.;cccccccccccc:   CPU: Intel Pentium G4560 (4) @ 3.500GHz 
cccccc:0MMKxdd:;MMMkddc.;cccccccccccc;   GPU: Intel HD Graphics 610 
ccccc:XM0';cccc;MMM.;cccccccccccccccc'   Memory: 528MiB / 7829MiB 
ccccc;MMo;ccccc;MMW.;ccccccccccccccc;
ccccc;0MNc.ccc.xMMd:ccccccccccccccc;                             
cccccc;dNMWXXXWM0::cccccccccccccc:,                              
cccccccc;.:odl:.;cccccccccccccc:,.
:cccccccccccccccccccccccccccc:'.
.:cccccccccccccccccccccc:;,..
  '::cccccccccccccc::;,.
```

My homelab got a bit of an upgrade.

## Services

I'm trying out Podman instead of Docker because it has a cool Cockpit plugin and I like simple admin panels like it.

- Syncthing
- Home Assistant
- Jellyfin


I also have a samba share for all things that I don't want to put inside SyncThing, Jellyfin or other thing.

![Synthing Running](SyncthingWorking.png)