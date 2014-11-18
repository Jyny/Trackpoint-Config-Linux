trackpoint-config
====================
this is my trackpoint files on x230 with archlinux   

##10-trackpoint.rules   
Configure for speed and sensitivity    
udev rules file under "/etc/udev/rules.d"   

find out the best speed and sensitivity for your own   
try it with the commend below first    

    echo 128 | sudo tee /sys/devices/platform/i8042/serio1/serio2/speed    
    echo 255 | sudo tee /sys/devices/platform/i8042/serio1/serio2/sensitivity    
  
##20-trackpoint.conf   
Trackpoint config file under "/etc/X11/xorg.conf.d"   

