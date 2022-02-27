# Getting started

Download the executable and extract it anywhere you want.

# Configuring

Configure the `config.ini` inside the root directory.
It is highly recommended to enable `force_kill` by setting the parameter to `true`.

# Using Firefox

Before starting the executable it's necessary to configure the firefox browser to avoid javascript timeouts or general freezing by ad bloating.
Type `about:config` in the URL bar and search for the following variables:
|       Variable         | Result
|----------------|-------------------------------|
|`browser.sessionstore.resume_from_crash`|`false`
|`dom.max_script_run_time`|`999999999`            

## Additional Addons

[eBesucher](https://addons.mozilla.org/de/firefox/addon/ebesucher-addon1) (Firefox) <br/>
[Popupblocker](https://addons.mozilla.org/de/firefox/addon/popupblockerall) (Firefox) - ([Settings #1](https://i.imgur.com/8gFfNt6.png), [Settings #2](https://i.imgur.com/s8Om9qQ.png)) <br/>
[Disable HTML5 Autoplay](https://addons.mozilla.org/de/firefox/addon/disable-autoplay) (Firefox) <br/>


## Profiles

Using Window's Run type:
`firefox.exe -p`
It's necessary to setup a surfBar profile called `ebesucher1` while using Firefox.


## Run

Run the executable and let the tool do the rest for you. It randomizes the startup intervals to spoof bot like behavior.<br/>
  <img width="977" height="510" src="https://i.imgur.com/rf52GKS.png">
