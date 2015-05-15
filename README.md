# admintools
Utilities for managing domains on a Debian 8 box

## Note
This is all because I was too lazy to write a bunch of configuration for all the domains I was managing.
It works on my box, a Linode with Debian 8 installed.

If it doesn't work for you, feel free to change around. Keep committing back to this project so that we can reach a global admin tool.

## Installation
Clone the repository and do `sudo ./install`. This will install the files under `/lib/admintools`. You can exchange `/lib` by passing in your desied prefix: `sudo ./install /opt/` will install under `/opt/admintools`, instead.

You will need to do one of the following for things to start working:
 1. `sudo . /etc/profile.d/admintools.sh` to populate the environment
 2. log out of your current session and log back in
 3. `export ADMINTOOLS_HOME=/lib/admintools` or wherever it is that you have installed the admin tools
 
## Usage
Everything is pretty self-explanatory and there is help available for most of the stuff. But you can get started by executing `sysadmin` using the super user credentials.
