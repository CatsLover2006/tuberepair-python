# TubeRepair server, using Flask and Jinja2.
- __A self-hosting solution, edit the backend to your likings.__
- __Fetches API from Invidious with no key needed.__
- Works from 1.0.0 to 1.2.1 (Classic YouTube soon!)
- ⚠️ This project is usable now, but still in beta. You can help in [bag's discord](https://discord.bag-xml.com) ⚠️
- (To bag.xml: I'm not fixing it)

Thanks to nugg3t for the hosting: https://tuberepair.nugg3t.xyz/

# Features
- Cache API responses
- Customizable config

### In the future
- Based all requests via innertube (ditching invidious and request to youtube Private API directly)
- Private server with password protection and secrets

# Setup
Make sure you have Python (3.8 minimum) and virtualenv (optional) installed.
```bash
# Download
git clone https://github.com/kendoodoo/tuberepair-python
cd tuberepair-python

# Preparing virtualenv
# You can just skip to pip, but for good measures.
virtualenv tuberepair
source tuberepair/bin/activate
pip install -r requirements.txt

# Running
python main.py
```

# Contributors

- [kendoodoo](https://github.com/kendoodoo)
- [SpaceSaver](https://github.com/SpaceSaver) (YouTube Private API, HLS playback filter)
- (et al.)
