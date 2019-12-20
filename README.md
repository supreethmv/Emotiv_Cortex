# Cortex API: Python

**Login**, **Download** and **Install** the Emotive Cortex Service from:
https://www.emotiv.com/my-account/downloads/
The Cortex service is a background process that communicates with the EMOTIV headsets and the EMOTIV cloud. It is also a WebSocket  server that uses the JSON-RPC protocol.

**Start the Cortex service**

**Clone this repo**
https://github.com/supreethmv/Emotiv_Cortex.git

**Activate the Virtual Environment**
local\path\of\repo\CortexENV\Scripts\activate

**Run**
python example.py
You'll have to provide access to this app in the Cortex Service 

**Issue**
The web socket port the app is listening to is 6868 inside the docker container