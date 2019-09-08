# lirc_web
Based on Alex Bain's work (https://github.com/alexbain/lirc_web)

This is only to share my config for my Universal Remote. 
For setup, refer directly to Alex Bain's Github as this is completely based on his work. 

Each file and directory in my config on my RPi is located at the exact same path as it is in this Github repository


Personal note: 
lirc_web now located at /usr/local/lib/node_modules/lirc_web
/usr/local/lib/node_modules/lirc_web/node_modules/lirc_node/lib/irsend.js modified. IRSend function modified from 'irsend' to 'irsend -# 5' to compensate for Buster kernel updates messing up with lirc irsend SEND_ONCE
