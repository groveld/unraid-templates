# unraid-templates

Docker templates for use with Unraid's dockerMan Docker management feature.

## Usage

Firstly you need to be running Unraid version 6.2 or later, once installed follow the instructions below:

1. Navigate to the ***Docker*** tab and then go to the ***Template Repositories*** section in the Unraid webui
2. Enter in a URL of `https://github.com/groveld/unraid-templates` in the ***Template repositories*** field
3. Click on the ***Save*** button
4. Click back to the ***Docker*** tab and then click on the ***Add Container*** button
5. Click on the ***Template*** dropdown menu and select the desired Docker image
6. Click the ***Advanced View*** toggle on the top right and fill in required fields e.g. volume data, environment variables etc
7. Click on the ***Create*** button at the bottom of the window to begin pulling down the Docker image
8. Once the image is downloaded you should see it appear in the ***Docker Containers*** section

## WatchDog
<img src="groveld/images/watchdog.png" alt="WatchDog" height="100"/>

A simple Node service which checks the status of a Docker Container and returns a RESTful response. It can also be used to issue start, stop, and restart commands. The primary purpose of this service is to interface with Home Assistant. Build automations/notifications for all of your docker containers and much more!

- Application Site: https://watchdog.groveld.com/
- Docker Hub: https://github.com/users/groveld/packages/container/package/watchdog
- Github: https://github.com/groveld/discord-watchdog

## DSMR Reader
<img src="groveld/images/dsmrreader.png" alt="DSMR Reader" height="100"/>

Open-source, non-commercial reader for (Dutch) smart meters supporting the DSMR protocol.

- Application Site: https://dsmr-reader.readthedocs.io/
- Docker Hub: https://hub.docker.com/r/xirixiz/dsmr-reader-docker
- Github: https://github.com/dsmrreader/dsmr-reader

___

If you appreciate my work, then please consider buying me a beer :D

[![PayPal](groveld/images/donate.png)](https://paypal.me/groveld)
