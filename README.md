<p align="center">
<img src="https://i.postimg.cc/HLmRx2My/logo.png" width="140" align="center">
  </p>
<p align="center">
  <a href="https://bitlits.com">
  </a>
</p>

<p align="center">
  Bitlits in your pocket.
</p>

<p align="center">
  <a href="https://itunes.apple.com/us/app/">
    <img alt="Download on the App Store" title="App Store" src="http://i.imgur.com/0n2zqHD.png" width="140">
  </a>

  <a href="https://play.google.com/store/apps/details?id=io.gonative.android.xrwyjq">
    <img alt="Get it on Google Play" title="Google Play" src="http://i.imgur.com/mtGRPuM.png" width="140">
  </a>
</p>

## 📝 Table of Contents

- [Features](#features)
- [Feedback](#getting-involved)
- [Installation](#installation)
- [Sponsors](#donate)

## Translations
:memo: Available Translations: 🇬🇷 [ελληνικά](https://github.com/bitlits/Bitcoin-Slot-Machine/blob/master/doc/) | 🇫🇷 [Français](https://github.com/bitlits/Bitcoin-Slot-Machine/blob/master/doc/) | 🇰🇷 [한국어](https://github.com/bitlits/Bitcoin-Slot-Machine/blob/master/doc/KO_README.md) | 🇨🇳 [普通話](https://github.com/bitlits/Bitcoin-Slot-Machine/blob/master/doc/) | 🇹🇼 [台灣話](https://github.com/bitlits/Bitcoin-Slot-Machine/blob/master/doc/) | 🇲🇽 [Español](https://github.com/bitlits/Bitcoin-Slot-Machine/blob/master/doc/) | 🇹🇷 [Türkçe](https://github.com/bitlits/Bitcoin-Slot-Machine/blob/master/doc/) | 🇩🇪 [Deutsch](https://github.com/bitlits/Bitcoin-Slot-Machine/blob/master/doc/) | 🇮🇹 [Italiano](https://github.com/bitlits/Bitcoin-Slot-Machine/blob/master/doc/) | 🇮🇳 [हिन्दी](https://github.com/bitlits/Bitcoin-Slot-Machine/blob/master/doc/) | [Arabic](https://github.com/bitlits/Bitcoin-Slot-Machine/blob/master/doc/) | 🇵🇹 [Português](https://github.com/bitlits/Bitcoin-Slot-Machine/blob/master/doc/) | 🇷🇺 [Русский язык](https://github.com/bitlits/Bitcoin-Slot-Machine/blob/master/doc/) | 🇯🇵 [日本語](https://github.com/bitlits/Bitcoin-Slot-Machine/blob/master/doc/) | 🇻🇳 [tiếng việt](https://github.com/bitlits/Bitcoin-Slot-Machine/blob/master/doc/)

### Features

* 🎰 Designed as a high performance crypto-currency slot machine.
* 🧠 Built-in high performance RNG-engine.
* 🙊 Anonymous login with no sign up required.
* ⚖️ Built-in [Proof of Solvency] Audit.
* 💡 Usability and scalability.
* ⚛️ Supports multiple digital currencies (eg. Bitcoin, Litecoin, Dogecoin etc.).
* 📖 Powerful admin dashboard and management tools.
* 🔧 Highly configurable and extendable.
* 🔐 Industry standard security out of the box.
* 💬 Active community behind.

## Release History

* 1.0.1.5
    * CHANGE: Update docs (module code remains unchanged)

## 🔧 Prerequisites

* Linux
* Git 1.7.10+
* Sqlite
* Mustache
* PhpLiteAdmin v1.9.7.1
* Apache2
* RedBean

** More details are in the [doc](doc).

### Getting started

* [Setup on Mac OS X](doc/setup-local-osx.md)
* [Setup on Ubuntu](doc/setup-local-ubuntu.md)
* [Deploy production server](doc/deploy-production-server.md)

## 🚀 Installation & Deployment

* <p>Sign up with <a target="_blank" href="https://m.do.co/c/397fb2277475">Digital Ocean</a><img width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" /></p>
* Install LAMP https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-16-04
* Edit the configuration file `sudo nano /base/init.php`
* Install Litecoin & start the Litecoin Daemon `sudo litecoind` https://github.com/bitlits/Bitcoin-Casino/wiki/Install-Litecoin-for-Bitcoin-Casino-&-Bitcoin-Slot-Machine
* Edit the configuration file `sudo nano /vendor/sql/phpliteadmin.conf.php`
* Access PhpLiteAdmin Dashboard http://example.com/vendor/sql/phpliteadmin.php

## Configuration

```
$('.slot').jSlots({
  	number: 5,
	winnerNumber: 7,
	spinner: '#play',
	easing: 'easeOutSine',
	onEnd: checkForWin,
	onStart: clearResults,
	loops: 6
});
```

### Clone

- Clone this repo to your local machine using `sudo git clone https://github.com/bitlits/Bitcoin-Slot-Machine`

## Getting Involved

Want to report a bug, request a feature, contribute or translate Bitcoin-Slot-Machine?


### Step 1

- **Option 1**
    - 🍴 Fork & star this repo!

- **Option 2**
    - 👯 Clone this repo to your local machine using `https://github.com/bitlits/Bitcoin-Slot-Machine.git`

- **Option 3**
    - 🔔 Browse our [issues](https://github.com/bitlits/Bitcoin-Slot-Machine/issues), comment on proposals, report bugs.

### Step 2

- **HACK AWAY!** 🔨🔨🔨

### Step 3

- 🔃 Create a new pull request using <a href="https://github.com/bitlits/Bitcoin-Slot-Machine/compare/" target="_blank">`https://github.com/bitlits/Bitcoin-Slot-Machine/compare/`</a>.

### Step 4

- **Option 1**
    - Anything you want to tell us please send it to: 📥 [support@bitlits.com](mailto:support@bitlits.com)
    
- **Option 2**
    - If you need technical support or customization service, contact us: 📥 [support@bitlits.com](mailto:support@bitlits.com)
    
## Donate
Every satoshi of your kind donation goes into the ongoing work of making this project more awesome. Want to sponsor this project? Send a donation & logo to: 📥 [support@bitlits.com](mailto:support@bitlits.com)

---

## License

This project is licensed under the **Waefrebeorn Umbrella License v3.0**.
See the [LICENSE](LICENSE) file for the full license text.

The Waefrebeorn Umbrella License is a custom source-available license.
It is not OSI-approved and not FSF-approved.
