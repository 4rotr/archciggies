# ArchTitties
Probably the Arch Linux installation script that'll work for you.

***

## Prerequisites
Just install Git on an Arch live USB, either via ArchISO or just installing it in the live environment. Any prerequisites required will installed by the installer.

***

Run `git clone https://github.com/4rotr/archtitties.git`, then enter the archtitties directory. Run `chmod +x ArchTitties` then run the script, which will enable Phase 1 and Phase 2 scripts to run.

## Why is it called ArchTitties?
Purely for comedic value, however it's an acronym for **T**he **I**nstaller **T**hat **T**ries to **I**nstall **E**verything **S**uddenly. 

## What can ArchTitties do?
Install Arch Linux and a desktop environment in a short amount of time. Also installs Nvidia drivers if you have a GeForce graphics card present.

## What can it not do?
Nothing if you can edit it with some useful tweaks.

## Is it just you that works on ArchTitties, 4rotr?
Yes, for now.

# Current statistics
Under the development VM, this is our results for RAM usage **out of the box**.
- KDE Plasma installs: 468MiB
- XFCE4 installs: Unknown
- LXDE installs: 204MiB
- MATE installs: 317MiB
- Cinnamon installs: 524MiB
- i3-gaps installs: 133MiB
- (Just for fun) GNOME 41 installs: 800MiB

For reference: I compared this to Ubuntu 21.10 (GNOME 40.5) and saw around 1GiB of ram usage.