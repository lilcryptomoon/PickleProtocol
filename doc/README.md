PickleProtocol Core
=============

Setup
---------------------
PickleProtocol Core is the original PickleProtocol client and it builds the backbone of the network. It downloads and, by default, stores the entire history of PickleProtocol transactions (which is currently more than 7 GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download PickleProtocol Core, visit [pickleprotocol.org](https://pickleprotocol.org).

Running
---------------------
The following are some helpful notes on how to run PickleProtocol on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/pickleprotocol-qt` (GUI) or
- `bin/pickleprotocold` (headless)

### Windows

Unpack the files into a directory, and then run pickleprotocol-qt.exe.

### OS X

Drag PickleProtocol-Core to your applications folder, and then run PickleProtocol-Core.

### Need Help?

* See the documentation at the [PickleProtocol Wiki](https://pickleprotocol.info/)
for help and more information.
* Ask for help on [#pickleprotocol](http://webchat.freenode.net?channels=pickleprotocol) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=pickleprotocol).
* Ask for help on the [PickleProtocolTalk](https://pickleprotocoltalk.io/) forums.

Building
---------------------
The following are developer notes on how to build PickleProtocol on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The PickleProtocol repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Travis CI](travis-ci.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [PickleProtocolTalk](https://pickleprotocoltalk.io/) forums.
* Discuss general PickleProtocol development on #pickleprotocol-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=pickleprotocol-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
