# Discord-QR-Auth-Client
A Client to communicate with Discord's QR Code login auth server
to easily retrieve useful information about your account
(including token.)

## How to use
Prerequisites:
* Have python 3.6+ installed (I recommend python 3.8)
* A Discord client that can scan QR codes (your phone)

Optional:
* Uncomment `numpy` and `wsaccel` in requirements.txt for slightly better performance (you really don't need to do this)
* Enable debug mode by modifying `debug=False` in server.py

### Steps
1. `python3 -m pip install -U -r requirements.txt`
2. `python3 server.py`
3. A QR code wil pop up. Scan it using your phone
(either using discord or a generic QR code scanner)
4. The script will ask you to save the info.
5. Close the QR code image. The script will not do this for you,
and it prevents confusion when using the script multiple times.