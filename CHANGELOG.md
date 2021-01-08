# Changelog
### Version 1.6.1 ###
  DNS Servers track active eMark nodes in real-time and,
  when queried, they give back a short list of the best nodes to connect to.
- Adds two DNS Servers:
1. dnsseed.deutsche-emark.cc	<--- NOTE: the Top-Level Domain is  ".CC" for Crypto Currency ! 
1. dnsseed.emarks.cc		<---	Crypto Currency, top level domain (TLD)    

 - Also adds some static hard-coded nodes as backup
 
### Version 1.6.0 ###
- Openssl v 1.1 support
- fix boost-1.66 incompatibilities
- Support boost 1.70

### Version 1.5.0 ###
- Lots of Security Patches
- Compatibility with newest Packages
- Update ProcessGetData for MerkleHashes on upcoming Android QT
- faster Blockchainsync
- nStakeMaxAge removed for staking Coins >2 Years
- StakeSplit set to 10000 DEM
- Orphan Blocks massivly REDUCED ! ( tested 1 Week with lots of POW/POS Wallets running simultaneously)
- new Nodes and Checkpoints
- TX Comments will shown up in QT Wallet

### Version 1.4.0: Hardfork 15.05.2016 00.00.00 GMT 
A reload the blockchain is necessary.
Version < 1.4.0 will no longer work.

### Version 1.3.0: support LevelDB 
(you must reload DB, if you don´t want, version 1.1.0 works fine (BerkleyDB). Download [from here](https://github.com/emarkproject/eMark/releases ))
do not use Version 1.2.x. You can loose Coins!

### eMark specification ###
- SHA256D, Proof of Work + Proof of Stake
- max 210 Million Proof of Work Coins
- 3.8% annual stake per year, 30 Days Coin-Age required
- 50 coins per block
- 2 minute block targets
- 100 blocks to coin maturation
- 140 Character Transaction Messaging

### Mandatory Wallet Update ###
### from 1415750400; // 12 Nov 2014 00:00:00 GMT ###
### Wallet Version V1.0.x no longer work ###
