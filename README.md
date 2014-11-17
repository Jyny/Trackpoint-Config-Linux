trackpoint-config
====================
this is my trackpoint files on x230 with archlinux   

##10-trackpoint.rules   
udev rules file at "/etc/udev/rules.d"   
Configure for speed and sensitivity   

try the best speed and sensitivity for your own   
you can test it with the cmd first    

    echo 128 | sudo tee /sys/devices/platform/i8042/serio1/serio2/speed    
    echo 255 | sudo tee /sys/devices/platform/i8042/serio1/serio2/sensitivity    
  
##20-trackpoint.conf   
Trackpoint config file at "/etc/X11/xorg.conf.d"   

