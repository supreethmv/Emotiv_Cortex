# Cortex API: Python

**Login**, **Download** and **Install** the Emotive Cortex Service from:
https://www.emotiv.com/my-account/downloads/
The Cortex service is a background process that communicates with the EMOTIV headsets and the EMOTIV cloud. It is also a WebSocket  server that uses the JSON-RPC protocol.

**Clone this repo**
https://github.com/supreethmv/Emotiv_Cortex.git

**Activate the Virtual Environment**
local\path\of\repo\CortexENV\Scripts\activate

**Run**
python example.py

**Issue**
In order to publish the container port 6868 to the host machine, the port 6868 in the local machine is already in use by the Cortex Websocket server.