This project is a bash script that aims to setup a WireGuard VPN on a Linux server, as easily as possible!
Original rep: https://github.com/angristan/wireguard-install.git

Usage
Download and execute the script. Answer the questions asked by the script and it will take care of the rest.

curl -O https://raw.githubusercontent.com/angristan/wireguard-install/master/wireguard-install.sh
chmod +x wireguard-install.sh
./wireguard-install.sh
It will install WireGuard (kernel module and tools) on the server, configure it, create a systemd service and a client configuration file.

Run the script again to add or remove clients!
