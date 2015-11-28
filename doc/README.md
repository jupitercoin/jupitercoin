Jupitercoin Core 1.10
==================

Setup
---------------------
[Jupitercoin Core](http://jupitercoin.com/) is the reference Jupitercoin client and it builds the backbone of the network. However, it downloads and stores the entire history of Jupitercoin transactions (which is currently several GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

Running
---------------------
The following are some helpful notes on how to run Jupitercoin on your native platform.

### Unix

You need the Qt4 run-time libraries to run Jupitercoin-Qt. On Debian or Ubuntu:

	sudo apt-get install libqtgui4

Unpack the files into a directory and run:

- bin/32/jupitercoin-qt (GUI, 32-bit) or bin/32/jupitercoind (headless, 32-bit)
- bin/64/jupitercoin-qt (GUI, 64-bit) or bin/64/jupitercoind (headless, 64-bit)



### Windows

Unpack the files into a directory, and then run jupitercoin-qt.exe.

### OSX

Drag Jupitercoin-Qt to your applications folder, and then run Jupitercoin-Qt.

### Need Help?

* See the documentation at the [Bitcoin Wiki](https://en.bitcoin.it/wiki/Main_Page)
for help and more information.
* Ask for help on [#jupitercoin](http://webchat.freenode.net?channels=jupitercoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=jupitercoin).
* Ask for help on the [BitcoinTalk](https://bitcointalk.org/) forums, in the [Jupitercoin thread](https://bitcointalk.org/index.php?topic=361813.0).

Building
---------------------
The following are developer notes on how to build Jupitercoin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OSX Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Jupitercoin repo's [root README](https://github.com/jupitercoin/jupitercoin/blob/master/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Resources
* Discuss on the [BitcoinTalk](https://bitcointalk.org/) forums, in the [Jupitercoin thread](https://bitcointalk.org/index.php?topic=361813.0).
* Discuss on [#jupitercoin-dev](http://webchat.freenode.net/?channels=jupitercoin-dev) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=jupitercoin-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the Bitcoin developers for use in [Bitcoin Core](https://www.bitcoin.org/). 
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
