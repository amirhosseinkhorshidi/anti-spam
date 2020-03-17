# Installation

To install everything in one command, use:

```sh
cd $HOME && git clone https://github.com/amirhosseinkhorshidi/anti-spam.git && cd anti-spam && chmod +x amirhossein.sh && ./amirhossein.sh install && ./amirhossein.sh
```

#### If you see an error, use:

```sh
# Let's install libreadline-dev
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev ppa-purge python3-pip python3-dev
```
```sh
# setup and execute the redis
sudo pip3 install redis
sudo service redis-server restart
```
```sh
# Optional
sudo add-apt-repository ppa:ubuntu-toolchain-r/test
sudo apt-get update
sudo apt-get upgrade
sudo apt-get dist-upgrade
sudo ppa-purge
```
* * *

## setup sudo id and execute the bot
Input your ID at line 93 and line 4 in bot.lua and line 2 in tools.lua and line 16 in config.lua
#### for example
  ```sh
  #Use NANO App
  nano Bot/bot.lua 
  #Edit it as Sample
  CTRL + X
  Y
  INTER 
  ```

### launch your bot with screen
```sh
cd anti-spam
screen ./amirhossein.sh
```
### Commands
* Send help in the group for get commands list.

* You can use #, ! or / to begin all commands.

### Developers
[amirhossein](https://github.com/amirhosseinkhorshidi) ([website](https://amirhosseinkhorshidi.ir))
