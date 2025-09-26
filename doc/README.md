SquardCoin Core
==========

This is the official reference wallet for SquardCoin digital currency and comprises the backbone of the SquardCoin peer-to-peer network. You can [download SquardCoin Core](https://www.squardcoin.org/downloads/) or [build it yourself](#building) using the guides below.

Running
---------------------
The following are some helpful notes on how to run SquardCoin Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/squardcoin-qt` (GUI) or
- `bin/squardcoind` (headless)

### Windows

Unpack the files into a directory, and then run squardcoin-qt.exe.

### macOS

Drag SquardCoin Core to your applications folder, and then run SquardCoin Core.

### Need Help?

* See the [SquardCoin documentation](https://docs.squardcoin.org)
for help and more information.
* Ask for help on [SquardCoin Discord](http://staysquardcoiny.com)
* Ask for help on the [SquardCoin Forum](/forum)

Building
---------------------
The following are developer notes on how to build SquardCoin Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [NetBSD Build Notes](build-netbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The SquardCoin Core repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Productivity Notes](productivity.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- Source Code Documentation ***TODO***
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [JSON-RPC Interface](JSON-RPC-interface.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* See the [SquardCoin Developer Documentation](https://squardcoin.readme.io/)
  for technical specifications and implementation details.
* Discuss on the [SquardCoin Forum](/forum), in the Development & Technical Discussion board.
* Discuss on [SquardCoin Discord](http://staysquardcoiny.com)
* Discuss on [SquardCoin Developers Discord](http://chat.squardcoindevs.org/)

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [squardcoin.conf Configuration File](squardcoin-conf.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [I2P Support](i2p.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [PSBT support](psbt.md)
- [Reduce Memory](reduce-memory.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
