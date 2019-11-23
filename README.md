# Beyondcoin Core Config Generator

[![Build Status](https://travis-ci.org/beyondcoin=project/beyondcoin-core-config-generator.svg?branch=master)](https://travis-ci.org/jlopp/beyondcoin-core-config-generator) An online generator is [available here](https://config.beyondcoin.io)

What is this?
-------------

[Beyondcoin](https://beyondcoin.io/) is a decentrailzed peer-to-peer economy that has no central authority.
Beyondcoin Core is the original and most popular Beyondcoin node software that anyone can use
to harness the full security features of the Beyondcoin protocol and operate without trusting any third parties. However,
there are over 140 configuration options for Beyondcoin Core and more are added with each release. This generator is meant
to expose and explain all of those options so that any user can make the most of the flexibility available to them.

Features
--------

Each configuration option is available via the user interface, grouped by what attributes they affect. For ease of
getting started with a new configuration, a variety of preset "node classes" are available on the right side of the
screen. Selecting a present will load our recommended base configuration for a node fitting that description, at which
point you can then tune the configuration at the single option level.

Available preset configurations:

* Mining: Suitable for miners who need to keep the entire UTXO set in RAM for fast block creation.
* Non-standard ports: For users who can't use the standard P2P or RPC ports
* Low Bandwidth: for users on metered connections; enforces bandwidth usage target
* Pruned: for users who want to limit their total disk usage. This also limits bandwidth usage.
* Raspberry Pi: for lower powered nodes with limited RAM & CPU
* Tor: for privacy conscious users
* Testnet: for developers using testnet coins
* Regtest: for developers creating their own test networks
* Non-Syncing: for developers who have a synced node but want to "freeze" the blockchain

License
-------

The Beyondcoin Core Config Generator is released under the terms of the GPL. See [LICENSE](LICENSE) for more information.
