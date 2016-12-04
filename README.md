silver-bot
============

[Installation](https://github.com/silver-bot/silvergroupTM/wiki/Installation)
------------
```bash
# Tested on Ubuntu 14.04, for other OSs check out https://github.com/yagop/telegram-bot/wiki/Installation
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev
```

```bash
# After those dependencies, lets install the bot
cd $HOME
git clone https://github.com/silver-bot/silvergroupTM.git
cd silvergroupTM
./launch.sh install
./launch.sh # Will ask you for a phone number & confirmation code.
```

