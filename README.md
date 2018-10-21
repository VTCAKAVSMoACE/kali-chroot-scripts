# kali-chroot-scripts

Scripts for accessing Kali as a chroot with X forwarding and network access.

### Assumptions

Your chroot is on an external disc labelled "kali" and the chroot dir is called "kali-<architecture>", where architecture is the dpkg arch for your system. I also assume that you have build this with debootstrap already.

### Notes

I would suggest modifying these scripts to match your environment exactly; this is more of a set of guidelines than anything. Furthermore, I would make a service to invoke the unchroot script at shutdown -- just in case.
