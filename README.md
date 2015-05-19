[![Build Status](https://travis-ci.org/GijsTimmers/radio.svg)](https://travis-ci.org/GijsTimmers/radio)

[![cc-logo](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/)


# radio
A small Python script to play various radio stations from a terminal.

## Dependencies:
- `pip`
- `mplayer`
- `argparse`
- `pyYAML`


You can install pip and mplayer via your package manager:

On Ubuntu:
    
    sudo apt-get install python-pip mplayer

On Arch:
    
    sudo pacman -S python2-pip mplayer
    
You can install argparse and pyYAML via `pip`:

    sudo pip install argparse pyYAML

## Usage

    ./radio.py <CHANNEL-ABBREVIATION>

e.g.

    ./radio.py r2nl
    ./radio.py stubru

Music will start playing automatically, press Enter or Q to exit.

## Adding other radio stations
There's a YAML file in this repository, called `zenders.yaml`. You can edit
this file to add other radio stations.
