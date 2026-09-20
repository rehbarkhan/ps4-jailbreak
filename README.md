## PS4 Jailbreak Code copied from raw13g
- Jailbreak from version 13.04 to 13.52

### Requirement
- PC
- Lan Cable

### Step 1
- Connect One end of ethernet to PC and other end to PS4 and disconnect wifi on both the devices

### Setup 2
#### Set the IP Address & Subnet mask in PC
- IP Address:       192.168.50.1
- Subnet mask:        255.255.255.0
- Default gateway:    leave blank
- DNS:                leave blank

### Setup 3
#### Delete Browser history, cache from PS4 web browser

### Setup 4
#### Manually set the IP address in PS4
- IP Address:       192.168.50.2
- Subnet Mask:      255.255.255.0
- Default Gateway:  192.168.50.1
- Primary DNS:      192.168.50.1
- Secondary DNS:    leave blank

### Setup 5
- Open command prompt and run ```server.cmd``` if you are on windows
- Open terminal and run ```cd src && python3 -m http.server 19876 --bind 0.0.0.0``` if you are on linux or macOs
#### Step 6 (Jail Break)
- Open browser and type http://192.168.50.1:19876
- Follow the in

Games can be downloaded from https://www.superpsx.com/

Special thankx to Developer repo : https://github.com/raw13g/raw13g.github.io