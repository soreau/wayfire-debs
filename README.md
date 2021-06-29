# wayfire-debs
Required updated packages for Wayfire on Ubuntu >=20.04.

## Installation
```
git clone https://github.com/soreau/wayfire-debs
sudo dpkg -i wayfire-debs/packages/wayfire-0.8.0/*.deb
sudo apt-get -f install
```
## Running
To run wayfire, logout and select wayfire session from the sessions list.

## Configuration
See the [wayfire wiki](https://github.com/WayfireWM/wayfire/wiki).

## Troubleshooting
Run `wayfire &> /tmp/wayfire.log` and post the log file to a pastebin service. Use the log to file an issue report or join `#wayfire` on `irc.libera.chat` for support.
