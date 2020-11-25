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
</Container>
```

## Credits

[watchdog.png](images/watchdog.png) - Image from [PNGEgg](https://www.pngegg.com/en/png-saejn)

___

If you appreciate my work, then please consider buying me a beer :D

[![PayPal](groveld/img/donate.png)](https://paypal.me/groveld)
