# Hassio OpenVPN Client AddOn

This is a Add-On for [Home Assistant](https://www.home-assistant.io) which enables
to tunnel the communication of your Home Assistant server with the world through 
a VPN connection. 

This Add-On is interesting especially for those of you
having a Google Home Mini and/or Amazon Alex integrated into your local Home Assistant
but don't want to expose it into the world and already have a trustworthy remote Server 
with a SSL certificate (acquired e.g. using [Certbot](https://certbot.eff.org/)).

The initial version of the Dockerfile to install the openvpn client was created 
by [TheSkorm](https://github.com/TheSkorm). Thanks for this. Base on his work, I've
added the following:

* The Addon-On will now ship with its own website based on [Flask](http://flask.pocoo.org/)
  in order to upload the configuration files.
* The client OpenVPN configuration is now possible via the Add-On configuration page.

