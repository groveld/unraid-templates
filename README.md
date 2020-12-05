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

## Base XML Template

```xml
<?xml version="1.0" encoding="utf-8"?>
<Container version="2">
  <Beta>True</Beta>
  <Category></Category>
  <Date></Date>
  <TemplateURL/>
  <Icon/>
  <Name></Name>
  <Repository></Repository>
  <Registry></Registry>
  <Support></Support>
  <Project></Project>
  <Overview></Overview>
  <DonateText/>
  <DonateLink/>
  <WebUI></WebUI>
  <Network>bridge</Network>
  <Shell>sh</Shell>
  <Privileged>false</Privileged>
  <ExtraParams/>
  <PostArgs/>
  <DonateImg/>
  <BaseImage/>
  <Branch/>
  <License/>
  <GitHub/>
  <BindTime/>
  <Banner/>
  <Version/>
</Container>
```

## Watchdog
<img src="groveld/images/watchdog.png" alt="Watchdog" height="100"/>
A simple Node service which checks the status of a Docker Container and returns a RESTful response. It can also be used to issue start, stop, and restart commands. The primary purpose of this service is to interface with Home Assistant. Build automations/notifications for all of your docker containers and much more!

- Docker container maintained at - https://github.com/groveld/discord-watchdog
- watchdog.png was grabbed from https://www.pngegg.com/en/png-saejn

## DSMR-reader
<img src="groveld/images/dsmrreader.png" alt="DSMR-reader" height="100"/>
Open-source, non-commercial reader for (Dutch) smart meters supporting the DSMR protocol.

- Docker container maintained at - https://github.com/xirixiz/dsmr-reader-docker
- the logo was grabbed from the [DSMR-reader](https://github.com/dsmrreader/dsmr-reader) repository

___

If you appreciate my work, then please consider buying me a beer :D

[![PayPal](groveld/images/donate.png)](https://paypal.me/groveld)
