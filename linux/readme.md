What is fstab?

Your Linux system's filesystem table, aka fstab, is a configuration table designed to ease the burden of mounting and unmounting file systems to a machine. It is a set of rules used to control how different filesystems are treated each time they are introduced to a system. Consider USB drives, for example. Today, we are so used to the plug and play nature of our favorite external drives that we may completely forget that operations are going on behind the scenes to mount the drive and read/write data.

In the time of the ancients, users had to manually mount these drives to a file location using the mount command. The fstab file became an attractive option because of challenges like this. It is designed to configure a rule where specific file systems are detected, then automatically mounted in the user's desired order every time the system boots. Not only is it less work over time, but it also allows the user to avoid load order errors that could eat up valuable time and energy.

https://www.redhat.com/sysadmin/etc-fstab#:~:text=What%20is%20it%3F,Consider%20USB%20drives%2C%20for%20example.
