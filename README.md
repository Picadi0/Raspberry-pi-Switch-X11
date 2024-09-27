# Raspberry-pi-Switch-X11
bellow the commmand lines fixes the blank screen when raspberry pi switches X11

sudo systemctl start vncserver-x11-serviced.service

sudo systemctl enable vncserver-x11-serviced.service

sudo raspi-config

go to advanced and choose the A6 switch it to X11
