
These configuration files should be copied in the /etc/config/ directory on your router.


IMPORTANT: In the default configuration the dnsmasq isn't started at boot. You should enable it on boot by creating a symlink into the /etc/rc.d/ like so:

 ln -s /etc/init.d/dnsmasq /etc/rc.d/S51dnsmasq


NOTICE: Before deploying the configs the psk2 passphrase should be changed.


NOTICE: The LAN ports are bridged with the freifunk network.
