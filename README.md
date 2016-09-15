# toggle_term
A simple script to allow you to have a pseudo drop down terminal
![example](https://raw.githubusercontent.com/edipox/toggle_term/master/example.png)

## Dependencies
This script depends on **xdotool** and **wmctrl**
```
sudo apt-get install wmctrl xdotool
```

## Installation
Just download the script file or execute the following commands in the terminal:
```
cd /tmp
wget https://raw.githubusercontent.com/edipox/toggle_term/master/toggle_term
sudo chmod +x toggle_term ; sudo mv toggle_term /usr/bin
```

## Customize
You can change the terminal app by editing the script file
```
my_term=pantheon-terminal
```
## Keybinding

### elementary OS
In elementary OS you can do this by changing the Keyboard configuration

Open switchboard in the keyboard settings section:
```
switchboard keyboard
```
Or search for **Keyboard** in slingshot launcher

Go to **Custom** and add a new command with your prefered short cut
![keyboard configuration](https://raw.githubusercontent.com/edipox/toggle_term/master/keyboard-config.png)

### Tip
Place the terminal window at the top wide open to get something like the first screenshot
