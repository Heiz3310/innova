# Innova [INN]
Tribus Algo PoW/PoS Hybrid Cryptocurrency

![logo](https://i.imgur.com/Zo0uzw9.png)

[![GitHub version](https://img.shields.io/github/release/innova-foundation/innova.svg)](https://badge.fury.io/gh/innova-foundation%2Finnova)
[![GitHub Commit Activity](https://img.shields.io/github/commit-activity/m/innova-foundation/innova)](https://github.com/innova-foundation/innova/pulse)
[![License: GPL v3](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/innova-foundation/innova/blob/master/COPYING)
[![Innova downloads](https://img.shields.io/github/downloads/innova-foundation/innova/total.svg)](https://github.com/innova-foundation/innova/releases)
[![Innova latest release downloads](https://img.shields.io/github/downloads/innova-foundation/innova/latest/total)](https://github.com/innova-foundation/innova/releases)

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Finnova-foundation%2Finnova&count_bg=%2346C019&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=Hits+-+Daily%2FTotal&edge_flat=false)](https://hits.seeyoufarm.com)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/innova-foundation/innova.svg)
![GitHub repo size in bytes](https://img.shields.io/github/repo-size/innova-foundation/innova.svg)
![Join the chat at https://discord.gg/mNM59znzNG](https://img.shields.io/discord/391676334956347395?label=Discord)

<a href="https://twitter.com/intent/follow?screen_name=Innova_Fdn"><img src="https://img.shields.io/twitter/follow/Innova_Fdn?style=social&logo=twitter" alt="follow on Twitter"></a>

[![Innova Snapcraft](https://snapcraft.io/innova/badge.svg)](https://snapcraft.io/innova)


[Links](#links)

## Intro

Innova is a true optionally anonymous, untraceable, and secure hybrid cryptocurrency.

Ticker: INN

Innova [INN] is an anonymous, untraceable, energy efficient, Proof-of-Work (Tribus Algorithm created by carsenk) and Proof-of-Stake cryptocurrency.

## Supported Operating Systems

* Linux 64-bit
* Windows 64-bit
* macOS 10.11+

## Install Innova with Snap on any Linux Distro

* `sudo apt install snapd`
* `sudo snap install innova`

* `innova` for running the QT
* `innova.daemon` for running innovad

## Specifications

* Total number of coins: 18,000,000 INN
* Ideal block time: ~15 seconds
* Stake interest: 6% annual static inflation
* Confirmations: 10 blocks
* Maturity: 75 blocks
* Min stake age: 10 hours

* Cost of Hybrid Collateral Nodes: 25,000 INN
* Hybrid Collateral Node Reward: 65% of the current block reward
* P2P Port: 14530, Testnet Port: 15530
* RPC Port: 14531, Testnet RPC Port: 15531
* Collateral Node Port: 14539, Testnet Port: 15539

* INN Magic Number: 0xb73ff4fa
* BIP44 CoinType: 116
* Base58 Pubkey Decimal: 102
* Base58 Scriptkey Decimal: 137
* Base58 Privkey Decimal: 230

## Technology

* Hybrid PoW/PoS Collateral Nodes
* Stealth addresses
* Ring Signatures (16 Recommended)
* Native Optional Tor Onion Node (-nativetor=1)
* Encrypted Messaging
* Multi-Signature Addresses & TXs
* Atomic Swaps using UTXOs (BIP65 CLTV)
* BIP39 Support (Coin Type 116)
* Proof of Data (Image/Data Timestamping)
* Fast ~15 Second Block Times
* Tribus PoW Algorithm comprising of 3 NIST5 algorithms
* Tribus PoW/PoS Hybrid
* Full decentralization
* Hyperfile - IPFS API Implementation with Anonymous Decentralized File Uploads (UI and RPC)
* Name Value System supporting the IDNS for fully & truly decentralized blockchain domains

## Links

* Official Website(https://innova-foundation.com/)
* Innova Twitter(https://twitter.com/innovacoin)
* Innova Discord Chat(https://discord.gg/mNM59znzNG)
* Innova Telegram Chat(https://t.me/innova_foundation)

## innovaqtubuntu.sh

Compile the latest Innova QT (Graphical Wallet) Ubuntu 16.04 or Ubuntu 18.04+

Credits to Buzzkillb for the creation of this bash script, original repository: https://github.com/buzzkillb/denarius-qt/

Compiles Innova QT Ubuntu 16.04 or 18.04, Grabs latest chaindata, and populates innova.conf with addnodes or can update a previous compile to the latest master branch.  
```bash -c "$(wget -O - https://raw.githubusercontent.com/innova-foundation/innova/master/innovaqtubuntu.sh)"```  

To turn on nativetor in innova.conf  
```nativetor=1```   

## Development process


Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
stable release versions of Innova.

Feature branches are created when there are major new features being
worked on by several people.

From time to time a pull request will become outdated. If this occurs, and
the pull is no longer automatically mergeable; a comment on the pull will
be used to issue a warning of closure. The pull will be closed 15 days
after the warning if action is not taken by the author. Pull requests closed
in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after
15 days from their last activity. Issues closed in this manner will be
labeled 'stale'.
