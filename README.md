Discord RP for Linux cuz i was bored

made by 0xmakarov

```bash
#clone the repo
git clone https://github.com/0xmakarov/discord-rpc-linux
cd discord-rpc-linux

#set up a venv and install dependencies
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt

#if pip gives you some trouble, use this instead
pip install -r requirements.txt --break-system-packages

#if it complains about "xcb"
sudo apt install libxcb-cursor0

#run it
python3 main.py
```

oh btw, before running, register an app on Discord:
1)  Go to https://discord.com/developers/applications → **New Application**
2) Copy the **Application ID** (that's your Client ID)
3) Under **Rich Presence → Art Assets**, upload the images you want to use

then jus paste the Client ID into the app, fill in Details/State, and hit **Activate Presence** (make sure Discord desktop is actually open first)
