# anydesk_install_astra_linux


# How to install AnyDesk on Astra Linux
# Step by step or use install_anyDesk.sh


sudo dpkg -i ./libpangox-1.0-0_0.0.2-5+b2_amd64.deb

sudo dpkg -i ./libgtkglext1_1.2.0-4_amd64.deb

sudo dpkg -i ./libminizip1_1.1-8+b1_amd64.deb

sudo dpkg -i ./anydesk_6.3.3-1_amd64.deb


# make sure permissions for all packages and script
sudo chmod 777 -R anydesk_install_astra_linux

# how to run install
sudo ./install_anyDesk.sh



