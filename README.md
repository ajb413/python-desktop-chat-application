# Python Desktop Chat Application

A [PubNub](https://www.pubnub.com/?devrel_gh=python-desktop-chat-application) powered Python 3 chat application. It's cross-platform desktop, thanks to PyQt. It sends and recieves chat messages using the PubNub network, so chat messaging is generic for devices/programming languages.

<img alt="PubNub Desktop Python Chat Application Example" src="https://i.imgur.com/qMvZX9L.png" width=288 height=288/>

This is a modified version of [Michael Herrmann's PyQt5 Example Chat](https://github.com/pyqt/examples/tree/_/src/11%20PyQt%20Thread%20example). I made it work with PubNub for the backend messaging.

## Install

 - First make a [free PubNub account](https://dashboard.pubnub.com/signup?devrel_gh=python-desktop-chat-application) to instantly get API keys. It's free up to 1 million messages per month, forever.
 - Clone this repository.
 - Copy and paste your free PubNub API keys onto line 18 of `chatapp.py`.

```python
pnconfig.publish_key = '__YOUR_PUBNUB_PUBLISH_KEY_HERE__'
pnconfig.subscribe_key = '__YOUR_PUBNUB_SUBSCRIBE_KEY_HERE__'
```

 - Save your code file.
 - Navigate to the project directory using your command line application.
 - Run this to install Python libraries:

```
pip3 install -r requirements.txt
```

## Run the Python Chat App
```
python3 chatapp.py
```
