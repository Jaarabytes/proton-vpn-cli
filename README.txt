##Commands for installation (Linux only)
```
sudo apt autoremove "protonvpn*" proton-vpn-gnome-desktop
sudo apt install ~/Downloads/protonvpn-stable-release_1.0.3_all.deb
sudo apt update
sudo apt-get install protonvpn-cli
```

After installation, login using:
```
protonvpn-cli login /<username/>
```
The input your password

To connect to a random server(connectin to specified servers has issues):
```
protonvpn-cli c -r
```
