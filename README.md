# `ConVid` - A dual mode video conferencing app

## How to install
* Use the below command to get started.

`wget -qO- https://gitlab.com/MexsonFernandes/bbb-install-script/-/raw/convid/bbb-install.sh | 
bash -s -- -w 
-a -w -g
-s convid.robomx.tech -e admin@robomx.tech -t
-v xenial-220
`

This will install Greenlight dashboard which support video recording and auth sessions.

Note: Some important flags
* Add '-t' to install the HTML5 client.
* Add '-g' for greenlight
* Add '-a' to integrate test apis.
* Add '-w' to install firewall which restricts access to port range of range 16384-32768.


* Add SSL to the domain
Use existing command with following add on.
`-s sitename.maindomain.tld -e email@address.tld` 

## Important Notes
* Replace **bigbluebutton/greenlight** with **registry.gitlab.com/mexsonfernandes/bbb-greenlight-ui:latest**.
* Every **greenlight-v2** release of greenlight is replaced by **registry.gitlab.com/mexsonfernandes/bbb-greenlight-ui**.

## Requirements

* Cloud Instance with config 4 Cores + 16 GB Ram.


## Reference
* [BBB install script](https://github.com/bigbluebutton/bbb-install)
* [Scalelite Github Repository](https://github.com/blindsidenetworks/scalelite)
* [Scaling BBB](https://events.ubuntunet.net/event/29/attachments/201/246/Installing_and_Scaling_BBB.pdf)