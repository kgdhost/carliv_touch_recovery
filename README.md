This is a touch recovery, virtual menu keys touch, for MTK powered phones, based on CWM.

The touch module is inspired mostly by <a href="https://github.com/scanno/CWM-Recovery-Modded-Touch-Vega">scanno touch recovery for Vega</a>. Also the ORS support is developed by Cannibal Open Touch Project Team.

To compile you need a device folder for your phone, a cm-10.1 building environment and my source. 
But:
- Make sure you put a flag on your BoardConfig.mk for screen resolution, just like in twrp:
```
DEVICE_RESOLUTION := 540x960
```

Enjoy!
