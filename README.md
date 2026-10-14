# ⚠️ DEPRECATED — do not use for Jungle4

**To install a Jungle4 node use the manual installation instead:
https://github.com/EOS-Jungle-Testnet/Node-Manual-Installation**

This auto-installer (last updated in 2022) can't bring up a working Jungle4 node anymore:

- It installs **EOSIO v2.0.13** (`update.sh`: v2.1.0 / v2.2.0-rc1) or builds `github.com/eosio/eos`. Jungle4 runs **AntelopeIO Spring v1.2.2** with Savanna consensus, and EOSIO can't sync it.
- It only supports Ubuntu 16.04 / 18.04 and CentOS 7.
- It doesn't create a BLS finalizer key, so a BP installed with it is skipped when the producer schedule is built.
- It downloads snapshots from `backup.cryptolions.io`, which is discontinued. Current snapshots are at https://jungletestnet.io/snapshots/.
- 5 of the 8 peers hard-coded in it are gone. The current list is at https://monitor4.jungletestnet.io/#p2p.

Both scripts now stop at start with a pointer to the manual installation. The original code is kept below that guard for reference.

Chain ID: 73e4385a2708e6d7048834fbc1079f2fabb17b3c125b146af438971e90716c4d

by: <a target="_blank" href="http://CryptoLions.io">CryptoLions.io</a>
