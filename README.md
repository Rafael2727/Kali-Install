# Kali-Install 
1st step: install termux&hackers  keyboard esc

Setting Up Our Environment

Next up, we would need some packages which we would need during the installation process.

2.update and upgrade the system with :

pkg update && pkg upgrade -y

termux-setup-storage

pkg install wget fish 

3.Copy&paste the link below.

$wget https://gitlab.com/kalilinux/nethunter/build-scripts/kali-nethunter-project/raw/master/nethunter-rootless/install-nethunter-termux

$chmod +x install-nethunter-termux

$./install-nethunter-termux
