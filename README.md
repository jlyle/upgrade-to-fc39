# upgrade-to-fc39

sudo dnf upgrade --refresh

sudo dnf install dnf-plugin-system-upgrade

sudo dnf system-upgrade download --releasever=39

sudo dnf system-upgrade reboot

# easy peasy  I had no issues, YMMV
