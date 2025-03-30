Plugin works with latest 2.81  https://github.com/evil-mad/eggbot/releases

1. Proceed with insctruction to install inscape for Mac (tested on 1.x with macOs Seqoia 15.4)
2. Search for extension folder where Eggbot is installed, usually: '/Users/{uiser}/Library/Application Support/org.inkscape.Inkscape/config/inkscape/extensions'
3. You have to modify 3 files, and modify single line in funcion findPort() in  ebb_serial.py  right-serial :

 `if port[0] == "/dev/cu.usbserial-1140":`
