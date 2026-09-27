# sysvinit Scripts

A collection of various sysvinit scripts we've written that might be useful to others.

As of the time of this writing, all scripts have been written with Debian-based systems such as Devuan and MX Linux in mind, however these scripts are of course modifiable to whatever distribution you may be running.

How to use:

1. `sudo cp` the scripts you wish to use into `/etc/init.d`.
2. `sudo chmod +x` every script you copied.
3. `sudo update-rc.d <script name> defaults` for every script you copied.
4. Start the services with `sudo service <script name> start` for each script.
