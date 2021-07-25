# node_red_switchbot_ble
Node Red example for operating Switchbot Bot via BLE

Very basic - for anyone that wants to operate a switchbot bot directly with Bluetooth control, could be improved massively: please share if you do improve it!
I could not find any examples on node red to work with the switchbot apart from their official API that requires the switchbot hub & cloud services... so I created this - which works well for me.

This only does the 'Press' command - other commands could easily be added.

You will need to install 'node-red-contrib-noble-bluetooth 0.9.1' first.

https://flows.nodered.org/node/node-red-contrib-noble-bluetooth

Use the switchbot local app to find out what the mac address for the switchbot you want to control and edit the nodes to suit (112233445566) eg (cc147bb13d77).

I've only tested this with my pi 4 - raspbian lite running node red v2.0.2

Import 'flows.json' in to Node Red.
