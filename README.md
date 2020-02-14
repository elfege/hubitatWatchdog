# hubitatWatchdog

This app runs using a couple motion sensors of your choice, preferably the ones you that are most frequently triggered in your home, so it detects when schedule / cron services are down which happens usually at the same moment that when your hub becomes unresponsive, and for the same causes (gridlocked database). When it detects such a low performance of your hub, it reboots it. It may need to reboot it twice in a row before it gets your hub stable and fully running again. 
