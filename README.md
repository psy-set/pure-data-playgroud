# PureData setup

## linux

### ubuntu/xubuntu 16.04

Keep in mind that the owner of the key may distribute updates, packages and repositories that your system will trust (more information).
```
echo 'deb http://download.opensuse.org/repositories/home:/aggraef/xUbuntu_16.04/ /' | sudo tee /etc/apt/sources.list.d/home:aggraef.list
curl -fsSL https://download.opensuse.org/repositories/home:aggraef/xUbuntu_16.04/Release.key | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/home:aggraef.gpg > /dev/null
sudo apt update
sudo apt install purr-data
```
