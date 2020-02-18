# hubitatWatchdog

This app runs using a couple motion sensors of your choice, preferably the ones that are most frequently triggered in your home, so to detect when schedule / cron services are down, which happens usually at the same moment than when your hub becomes unresponsive, and for the same causes (gridlocked database). When it detects such a low performance of your hub, it reboots it. 

This app can also ping another instance of the same app on a remote hub on your local network (local only)
