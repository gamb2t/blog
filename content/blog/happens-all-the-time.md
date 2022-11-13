---
title: "Happens All the Time"
date: 2022-11-11T13:17:00Z
draft: false
tags: [""]
---

- make efi and root partitions
- setup luks
- setup lvm
- edit /etc/default/grub to add the cryptdevice option
- install grub into the efi partition
- reboot, land in grub command line with no error

30mins of troubleshooting later
>oops, forgot to generate the grub.cfg
