Licode [http://lynckia.com/licode] Basic Example in Python

Install licode by following these instructions:
http://lynckia.com/licode/install.html

Open the licode_config.js and enter the relative path to static/recorded/ as the config.erizoController.recording_path (relative to licode/erizo_controller/erizoController).

INSTALL REQUIRED PACKAGES
pip install -r requirements.txt

MODIFY CONFIG
- rename config.py.example to config.py [Already done]
- change superserviceID and superserviceKey, get the values from licode_config.js in your licode directory
- set nuveHost to your licode host

RUN
python app.py
open http://localhost:5000
