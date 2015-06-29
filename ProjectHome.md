- You can click and type on the phone (we inject touch events to the touch device and create a new HID for typing), get screenshots (copied from the framebuffer device) in jpeg and png, record images in sequence

- start phone calls (it uses '/bin/system/service' from android)

- open webpages on the phone (it uses intents)

- browse, download from, upload to the SD card (it uses AjaXplorer so you can rename files, listen mp3, etc.)

- browse and read every files on phone

- adjust LCD backlight

- get the phone's location (GPS and network, it uses our JAVA code and shows the result on GoogeMaps)

- reading and writing SMS,

- exporting contacts, messages, call list in txt, csv, xml,

- chat with phone and other users

- terminal emulator with Shell In A Box

- user rights management, log

- works on wifi, 3g

- DynDNS support (it's a dinamic DNS service, after you register at dyndns.org, your phone will have an address like: myphone.homeip.net, this only works if you can reach your phone using its IP address)

- if your 3g internet provider blocks the incoming connection to your phone, then you cannot connect using its IP address or DynDNS, but you can connect through our server (the phone starts the connection like GoogleTalk does)

- SSL support for direct connections (it doesn't work thought our server, we are working on it) - this product includes cryptographic software written by Eric Young (eay@cryptsoft.com)

- opensource (it is licensed under General Public License)

- most of the functions uses only C++ part, which has very low memory footprint and almost no CPU use in idle.