
These configuration files should be copied in the /etc/config/ directory on your router.


IMPORTANT: In the default configuration the dnsmasq isn't started at boot. You should enable it on boot:

    /etc/init.d/dnsmasq enable


NOTICE: Before deploying the configs the passphrase ("key" in wireless) and the name of your wireless network ("ssid") should be changed.


NOTICE: The LAN ports are bridged with the freifunk network.
