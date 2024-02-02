A Watchdog device makes sure that your server is still running.
The included service will regularly write to that watchdog device. If it stops doing so, most likely due to a freeze, then the server will be rebooted.

This Watchdog better (only?) works if you have a hardware watchdog integrated in your server. It has only been tested on Raspberry Pi so far.
