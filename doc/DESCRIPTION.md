A watchdog service makes sure your server is still running and reboots it if necessary.  
It better (only?) works if your server has a [hardware watchdog device](https://en.wikipedia.org/wiki/Watchdog_timer).

The included sercice will regularly write to `/dev/watchdog`. If it stops, then the freeze is detected and server rebooted.

This app has only been tested on Raspberry Pi.
