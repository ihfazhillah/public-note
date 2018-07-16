# get the interface link

issue the `ip link` command. For wifi, it's started with char `w` like `wlan` or others.

# wifi mode in linux

when issuing `iwconfig` command, it's will display current mode of the wifi card.
- Managed means that the current card will be at client mode
- Master means that the current card will be the base mode (AP)

and to change mode, we can issue the following command:
```bash
iwconfig the-interface mode managed|master
```

# Get current connection information

issue `iwgetid`

get 

```
interface ssid
```

# Get / Scan wifi

`iw dev inteface scan`, for wifi name, you can issue grep `SSID`

