# Lychee

#### A great looking and easy-to-use photo-management-system.

*Since the 1st of April 2018 this project has moved to it's own Organisation (https://github.com/LycheeOrg) where people are able to submit their fixes to it. We, the Organisation owners, want to thank electerious (Tobias Reich) for the opportunity to make this project live on.*

![Lychee](https://camo.githubusercontent.com/b9010f02c634219795950e034f511f4cf4af5c60/68747470733a2f2f732e656c6563746572696f75732e636f6d2f696d616765732f6c79636865652f312e6a706567)
![Lychee](https://camo.githubusercontent.com/5484591f0b15b6ba27d4845b292cc5d3a988b3b9/68747470733a2f2f732e656c6563746572696f75732e636f6d2f696d616765732f6c79636865652f322e6a706567)

Lychee is a free photo-management tool, which runs on your server or web-space. Installing is a matter of seconds. Upload, manage and share photos like from a native application. Lychee comes with everything you need and all your photos are stored securely. Try the [Live Demo](https://ld.electerious.com) or read more on our [Website](https://LycheeOrg.github.io).

## Installation

To run Lychee, everything you need is a web-server with PHP 5.5 or later and a MySQL-Database. Follow the instructions to install Lychee on your server. [Installation &#187;](https://github.com/LycheeOrg/Lychee/wiki/Installation)

## How to use

You can use Lychee right after the installation. Here are some advanced features to get the most out of it.

### Settings

Sign in and click the gear in the top left corner to change your settings. If you want to edit them manually: MySQL details are stored in `data/config.php`. Other options and hidden settings are stored directly in the database. [Settings &#187;](https://github.com/LycheeOrg/Lychee/wiki/Settings)

### Update

Updating is as easy as it should be.  [Update &#187;](https://github.com/LycheeOrg/Lychee/wiki/Update)

### Build

Lychee is ready to use, right out of the box. If you want to contribute and edit CSS or JS files, you need to rebuild Lychee. [Build &#187;](https://github.com/LycheeOrg/Lychee/wiki/Build)

### Keyboard Shortcuts

These shortcuts will help you to use Lychee even faster. [Keyboard Shortcuts &#187;](https://github.com/LycheeOrg/Lychee/wiki/Keyboard%20Shortcuts)

### Dropbox import

In order to use the Dropbox import from your server, you need a valid drop-ins app key from [their website](https://www.dropbox.com/developers/apps/create). Lychee will ask you for this key, the first time you try to use the import. Want to change your code? Take a look at [the settings](https://github.com/LycheeOrg/Lychee/wiki/Settings) of Lychee.

### Twitter Cards

Lychee supports [Twitter Cards](https://dev.twitter.com/docs/cards) and [Open Graph](http://opengraphprotocol.org) for shared images ([not albums](https://github.com/electerious/Lychee/issues/384)). In order to use Twitter Cards you need to request an approval for your domain. Simply share an image with Lychee, copy its link and paste it in [Twitters Card Validator](https://dev.twitter.com/docs/cards/validation/validator).

### Imagick

Lychee uses [Imagick](https://www.imagemagick.org) when installed on your server. In this case you will benefit from a faster processing of your uploads, better looking thumbnails and intermediate sized images for small screen devices. You can disable the usage of [Imagick](https://www.imagemagick.org) in [the settings](https://github.com/LycheeOrg/Lychee/wiki/Settings).

### Docker

Browse the [Docker Hub Registry](https://hub.docker.com/r/kdelfour/lychee-docker/) for various automated Lychee-Docker builds. We recommend using [lychee-docker](https://hub.docker.com/r/kdelfour/lychee-docker/) by [kdelfour](https://github.com/kdelfour).

### Plugins and Extensions

The plugin-system of Lychee allows you to execute scripts when a certain action fires. Plugins are hooks, which are injected directly into Lychee. [Plugin documentation &#187;](https://github.com/LycheeOrg/Lychee/wiki/Plugins)

It's also possible to build extensions upon Lychee. The way to do so isn't documented and can change every time. We recommend using the plugin-system, when possible.

Here's a list of all available Plugins and Extensions:

| Name | Description | |
|:-----------|:------------|:------------|
| lycheesync | Sync Lychee with any directory containing photos | [More &#187;](https://github.com/GustavePate/lycheesync) |
| lycheeupload | Upload photos to Lychee via SSH | [More &#187;](https://github.com/r0x0r/lycheeupload) |
| Jekyll | Liquid tag for Jekyll sites that allows embedding Lychee albums | [More &#187;](https://gist.github.com/tobru/9171700) |
| lychee-redirect | Redirect from an album-name to a Lychee-album | [More &#187;](https://github.com/electerious/lychee-redirect) |
| lychee-watermark | Adds a second watermarked photo when uploading images | [More &#187;](https://github.com/electerious/lychee-watermark) |
| lychee-rss | Creates a RSS-Feed out of your photos | [More &#187;](https://github.com/cternes/Lychee-RSS) |
| lychee-FlashAir | Import from a Toshiba FlashAir WiFi SD card | [More &#187;](https://github.com/mhp/Lychee-FlashAir) |
| lychee-webroot | Controls photos accessibility and keeps Lychee files hidden | [More &#187;](https://github.com/Bramas/lychee-webroot) |
| lychee-create-medium | Generate missing medium size photos | [More &#187;](https://github.com/Bramas/lychee-create-medium) |

## Troubleshooting

Take a look at the [FAQ](https://github.com/LycheeOrg/Lychee/wiki/FAQ) if you have problems. Discovered a bug? Please create an issue here on GitHub!
