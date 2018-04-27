PIVX Core
=====================

Setup
---------------------
[PIVX Core](http://syndicate.org/wallet) is the original PIVX client and it builds the backbone of the network. However, it downloads and stores the entire history of PIVX transactions; depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more. Thankfully you only have to do this once.

Running
---------------------
The following are some helpful notes on how to run PIVX on your native platform.

### Unix

Unpack the files into a directory and run:

- bin/32/syndicate-qt (GUI, 32-bit) or bin/32/syndicated (headless, 32-bit)
- bin/64/syndicate-qt (GUI, 64-bit) or bin/64/syndicated (headless, 64-bit)

### Windows

Unpack the files into a directory, and then run syndicate-qt.exe.

### OSX

Drag PIVX-Qt to your applications folder, and then run PIVX-Qt.

### Need Help?

* See the documentation at the [PIVX Wiki](https://en.bitcoin.it/wiki/Main_Page) ***TODO***
for help and more information.
* Ask for help on [BitcoinTalk](https://bitcointalk.org/index.php?topic=1262920.0) or on the [PIVX Forum](http://forum.syndicate.org/).
* Join our Discord server [Discord Server](https://discord.syndicate.org)
* Join one of our Slack groups [PIVX Slack Groups](https://syndicate.org/slack-logins/) (Main community is replaced by Discord).

Building
---------------------
The following are developer notes on how to build PIVX on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OSX Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Pivx repo's [root README](https://github.com/PIVX-Project/PIVX/blob/master/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/bitcoin/doxygen/) ***TODO***
- [Translation Process](translation_process.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Resources

* Discuss on the [BitcoinTalk](https://bitcointalk.org/index.php?topic=1262920.0) or the [PIVX](http://forum.syndicate.org/) forum.
* Join the [PIVX-Dev](https://syndicate-dev.slack.com/) Slack group ([Sign-Up](https://syndicate-dev.herokuapp.com/)).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT/X11 software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.