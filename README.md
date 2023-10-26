## Simple OpenRC init scripts for Crowdsec and Crowdsec Firewall Bouncer ##

Usage:

Tested on Gentoo
Copy both crowdsec and crowdsec-firewall-bouncer to `/etc/init.d/`

Add both crowdsec and crowdsec-firewall-bouncer to the default runlevel
```rc-update add default crowdsec
rc-update add default crowdsec-firewall-bouncer```

start with
```/etc/init.d/crowdsec start
/etc/init.d/crowdsec-firewall-bouncer stop```
