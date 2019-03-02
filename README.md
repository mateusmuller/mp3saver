# mp3saver
This is a simple incremental back-up script that I have created for myself.

## What it does?
This script back-up automatically every .mp3 music on /home/$USER/Downloads to an external hard drive.

## How to use it?
You can either execute it manually or setup a crontab schedule like me.

* *$ git clone https://github.com/mateusmuller/mp3saver*
* *$ sudo mp3saver*

## Crontab configuration
This is my schedule:

* *30 21   * * *   root    /home/mateus/Scripts/shell/mp3saver*

Every day, on 21:30 it will execute it.

## Should I change something?
Yes, you have to change the variables according to your user and directories.
