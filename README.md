# openwrt-wan-status-led
Sets WAN status LED according to WAN ping test

## Installation

Copy 'wan_status_led' script to /etc/init.d ensuring it has +x execute 
permission. 

You will need to customize the specific LED path that you want to set, as it
 is currently set up for my NanoPI R6S, it will set the wan LED on for successful ping and off when ping is unsuccessful.

Run 'service wan_status_led enable' and then 'service wan_status_led start' to
 start it 

Alternatively you can enable and start it through the web ui through 'System'
 -> 'Startup'.

