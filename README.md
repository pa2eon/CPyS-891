<del><h1 align="center">CPyS-891</h1></del>
<del><p align="center">
    <img src="./images/icon.png" alt="TPOL CCH" width="754" height="464" />
</p></del>

___

This script is a CPS like for the Yaesu FT-891, it uses the CAT with the pyserial module to control the transceiver 
___
## 1) Installation :

`git clone https://github.com/F4JTV/CPyS-891.git `</br>
`cd CPyS-891`</br>
`sudo apt-get install python3-pip`</br>
`pip install -r requirements.txt`</br>
`python3 ./CPyS-891.py`</br>

___

## 2) Usage :

- Edit the CPyS.cfg and change the COM port (Windows) or the /dev/ttyUSB (Linux) and the baudrate folowing your rig.
- Do NOT use (in windows) high ports like COM10: or more .. the config parameters will not be correct reading in de application.
- The Live Mode will change immediatly the value parameters. If it is disabled, changes on the FT-891 will be applied when you trigger the "Send config to FT-891"
- For now, you can get all the parameters of the menu with "Get config from FT-891" on the menubar.

___

## 3) Dev plan :

- this script is still in development, for now, only the Menu of the FT-891 is implemented.

TODO: 
- Menu -> done
- Functions
- Memory -> in progress
- Reset the rig to default config -> done
- Save and open config files
- Presets for quick config
- About 
- Documentation

## 4) Thanks to contributors for there work and ideas:
PA2EON
