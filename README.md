# Discord-raspberry-pi-startup-notifier
This project is about how to send notification in discord through discord webhooks when raspberry pi boots up(after entering desktop).


**Requirements**


1. First download the zip file through command `git clone https://github.com/thinker010/Discord-raspberry-pi-startup-notifier.git` in  and extract in your raspberry pi.
2. Then copy the `main.desktop` file and paste it in here `/etc/xdg/autostart`.
3. Then paste the `main.py` to the pi folder at `/home/pi` (or where ever you want but you have to change the address of the `main.py` file in main.desktop)
4. Now go to the terminal and make the python file executable by typing `sudo chmod +x main.py`.
5. Now configure your code by typing your desired message.


Hoping this was helpful.:)




# HOW TO GET YOUR WEBHOOK URL:

https://support.discord.com/hc/en-us/articles/228383668-Intro-to-Webhooks





# Source: 

https://pypi.org/project/discord-webhook/
        
   https://www.hackster.io/kamal-khan/desktop-shortcut-for-python-script-on-raspberry-pi-fd1c63
