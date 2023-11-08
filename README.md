# upgrade-to-fc39 <br>
sudo dnf upgrade --refresh <br>
sudo dnf install dnf-plugin-system-upgrade <br>
sudo dnf system-upgrade download --releasever=39 <br>
sudo dnf system-upgrade reboot <br>
# easy peasy  I had no issues, YMMV
