# mp3saver
This is a simple incremental back-up script that I have created for myself.

## What it does?
This script back-up automatically every .mp3 music on /home/$USER/Downloads to an external hard drive.

## How to use it?
You can either execute it manually or setup a crontab schedule like me.

* *$ git clone https://github.com/mateusmuller/mp3saver*
* *$ sudo mp3saver*

## Crontab configuration
You may want to create softlink to another folder inside $PATH.

* *$ ln -s /home/mateus/Scripts/shell/mp3saver/mp3_saver /usr/local/bin

Therefore, on /etc/crontab you can call only the script name.

* *30 21   * * *   root    mp3_saver 1> /dev/null 2>&1*

Every day, on 21:30 it will execute it.

## Should I change something?
Yes, you have to change the variables according to your user and directories.
