# `ConVid` - A dual mode video conferencing app

## How to install
* Use the below command to get started.

`wget -qO- https://ubuntu.bigbluebutton.org/bbb-install.sh | 
bash -s -- -w -v xenial-22
-a -w -g
-s convid.robomx.tech -e admin@robomx.tech -t
-v xenial-22
`

This will install Greenlight dashboard which support video recording and auth sessions.

Note: Some important flags
* Add '-t' to install the HTML5 client.
* Add '-g' for greenlight
* Add '-w' to install firewall which restricts access to port range of range 16384-32768.


* Add SSL to the domain
Use existing command with following add on.
`-s sitename.maindomain.tld -e email@address.tld` 


## Requirements

* Cloud Instance with config 4 Cores + 16 GB Ram.


## Reference
* [BBB install script](https://github.com/bigbluebutton/bbb-install)
* [Scalelite Github Repository](https://github.com/blindsidenetworks/scalelite)