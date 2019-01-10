# C099-F9P ODIN-W2 Connectivity SW & ZED-F9P config files

These files allow quick configuration of the ODIN-W2 and ZED-F9P RTK receivers on the C099-F9P for WIFI peer to peer
base and rover operation. 

https://www.u-blox.com/en/product/c099-f9p-application-board

## RELEASE INFO - ODIN-W2 configuration

### Files
odinw2_base_udp_client.txt
odinw2_rover_udp_server.txt

### Dependencies
u-blox Connectivity Software 5.01/6.0.1 for ODIN-W2
u-blox s-center evaluation software for download of ODIN configuration files
C099-F9P-AppBoard-ODIN-W2-CSW_UserGuide_(UBX-18055649).pdf
			  
https://www.u-blox.com/en/product/s-center

https://www.u-blox.com/sites/default/files/C099-F9P-AppBoard-ODIN-W2-CSW_UserGuide_%28UBX-18055649%29.pdf

### DESCRIPTION
The C099-F9P enables two units to operate as a base and rover pair using the 
u-blox Connectivity Software 5.01/6.0.1 for ODIN-W2. This uses WIFI peer to peer data transfer.

The ODIN configuration txt files must be downloaded using s-center as detailed in
C099-F9P-AppBoard-ODIN-W2-CSW_UserGuide_(UBX-18055649). 

## RELEASE INFO - ZED-F9P configuration

### Files
f9p_base_config_forC099.txt
f9p_rover_config_forC099.txt
f9p_base_surveyin_disable.txt - (a cold start must be sent after this)
f9p_base_surveyin_start.txt
f9p_moving_base_config_forC099.txt
	  
### Notes
Not compatible with u-center legacy configuration file download. 
You must use new u-center, View/Generation 9 Configuration View/Advanced configuration  - Load and Send buttons. 
Return ZED-F9P to default configuration first before configuration file download.
	  
### Dependencies 
ZED-F9P HPG1.00 firmware (supplied on the C099-F9P until end of December 2018)
ZED-F9P HPG1.10 firmware for moving baseline operation (supplied on the C099-F9P after December 2018)
u-blox u-center evaluation software V18.11 

https://www.u-blox.com/en/product/u-center

## DISCLAIMER
Copyright (C) u-blox AG

u-blox reserves all rights in this deliverable (documentation, software, etc.,).
