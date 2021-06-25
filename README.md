# MTk_Bypass
Skip steps 1-5 after first usage

Install python(select "Add Python X.X to PATH")
Install libusb-win32
Launch filter wizard, click next
Connect powered off phone with volume+ button, you should see new serial device in the list. Select it and click install
Install pyusb, pyserial, json5 with command:
pip install pyusb pyserial json5
Run this command and connect your powered off phone with volume+ button, you should get "Protection disabled" at the end
python main.py
After that, without disconnecting phone, run SP Flash Tool
