## Add dial user
sudo useradd -G dialout,dip,users -m -g users -s /usr/sbin/pppd dial

## Set dial password
sudo passwd dial
