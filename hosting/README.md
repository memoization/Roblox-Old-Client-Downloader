## Steps to Host a Local Server.

1. Launch the desired place in studio and use the `Execute Script` menu option to start up the server. Select `server.lua`.
2. Launch studio again and open an empty (new) place.
3. Use the `Execute Script` menu option and finally select `join.lua`.

## Steps to Host a Public Server.
*Keep in mind that any running firewalls or antivirus programs may block the open port.*

1. Go into your router's settings and ensure that port forwarding is set to `1358` going to your machine's private ip.
2. Host the server following the same steps above.
3. On the player's end, provide or have the user edit the `HOST_IP` variable located in the `join.lua` script to have the host's [public ip](https://www.whatsmyip.org/).
4. Have the player use the `Execute Script` menu option and finally select `join.lua`.

## Notes
Keep in mind that the join and server scripts only work on older versions of studio < 2012. Results aren't guaranteed per client version.
