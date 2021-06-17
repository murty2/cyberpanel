# PLEASE DO NOT USE THIS SOFTWARE UNTIL I FIX THE FOLLOWING ISSUES

I have serious security concerns and doubts as to whether Cyberpanel install script is malicious. I appreciate the free software and the spirit of sharing the code publicly. It is noble and the actual software itself is good. But it seems the developers know how to ruin a good thing.

    - Poor coding. As if it is some sort of literary exercise in bad poetry. Random spaces, obscure error checking, no proper logic skills
    - The install scripts assume that you are running on a clean box physically in front of you. Indeed, it will mess up the OS and perform all kinds of things, borderline malicious, worse than other panels
    - Attempts to do DNS hijacking and breaking the networking in general. (Question for the genius who coded the install scripts: Is a running systemd-networkd necessary to achieve network connectivity in Linux?)
    - Passwords either insecure or in plain. Removes SELinux protection itself; not to mention attempt to add swap and other system level changes without user permission
    - Randomly downgrades dependencies. Never mind the security issues in this process

Cyberpanel is a good product and I hope someone forks it and takes it in the right direction. (If my time permits, I might do that myself)

(There is a false belief in the developer community that Windows devs immediately become Sys Admins and Security Admins when they start using Nano editor in Ubuntu. This is is not true. A good dev sticks to what he does best. Alternatively, just releases a Docker or virtual image instead of install scripts)


# CyberPanel

Webhosting control panel that uses OpenLiteSpeed as web server.

## Features

* Different Level Of users.
* Auto SSL.
* FTP Server.
* Light weight DNS Server (PowerDNS).
* PHPMYAdmin.
* Email Support (Rainloop).
* FileManager.
* PHP Managment.
* Firewall (FirewallD & ConfigServer Firewall Intregration).
* One click Backup and Restore.

# Supported PHPs

* PHP 5.3
* PHP 5.4
* PHP 5.5
* PHP 5.6
* PHP 7.0
* PHP 7.1
* PHP 7.2
* PHP 7.3
* PHP 7.4
* PHP 8.0

# Installation Instructions


```
sh <(curl https://cyberpanel.net/install.sh || wget -O - https://cyberpanel.net/install.sh)
```

# Resources

* [Official Site.](https://cyberpanel.net)
* [Documentation.](https://docs.cyberpanel.net)
* [Forums.](https://forums.cyberpanel.net)


