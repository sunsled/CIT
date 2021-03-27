# CIT

This script makes use of wttr.in to display the weather in your location. To use this script, wttr.in must be installed.

Installation instructions for wttr.in can be found here:

[chubin/wttr.in](https://github.com/chubin/wttr.in/blob/master/README.md) 

Download the /bin/motd script and place it in your usr/bin folder. Download the weather.service and weather.timer unit files and place it in
your /usr/etc/systemd/system folder.

Reload services by running the command:

>systemctl daemon-reload

Enable the weather.service unit file by running the command:

>systemctl enable weather.service

Enable the weather.service unit file by running the command:

>systemctl enable weather.timer
