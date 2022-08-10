# Getting Started

## Basics

max. supply = 100.000.000 BMB

1 BMB = 10.000 leaf

1 leaf = 0.0001 BMB

minimum transaction fee = 1 leaf

block time = 90 seconds

max. transactions in a block = 25.000

## Creating a Wallet

There currently are two different options for creating a wallet. Option A is using the keygen tool to generate a new keypair, option B is using the GUI wallet available [here](https://github.com/f10crypto/bamboowallet).

### Keygen + CLI (Linux / OSX)

**only use this option if you are familiar with linux and/or building executables**

Follow the getting started and building steps from the [official Bamboo repository](https://github.com/bamboo-crypto/bamboo/blob/master/README.md#getting-started). Build keygen and cli with `make keygen` and `make cli`. Run keygen to get a `keys.json` file. This file contains your wallet address, as well as public and private key. You can now use the cli you compiled earlier to send transactions from this wallet.
 

### GUI Wallet (Windows only)

Requirements: [webview2](https://go.microsoft.com/fwlink/p/?LinkId=2124703), [.NET](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net462)

Using the GUI wallet should be self explanatory, just download the exe, put it in a folder (it should be the only file in this folder) & run it. The most important thing to remember is that you need to have a backup of **both** your **mnemonic phrase and password**, restoring a wallet from mnemonic with a different password than originally used will result in a different wallet.

## Mining

Get dcrptd-miner from [here](https://github.com/De-Crypted/dcrptd-miner/releases/latest).

To get started you only need to edit config.json and replace "WALLET_ADDRESS_HERE" with your wallet address.

## Buying/Selling Bamboo

There's an USDT and a BTC trading pair on exbitron.com

[USDT](https://www.exbitron.com/trading/bmbusdt)

[BTC](https://www.exbitron.com/trading/bmbbtc)
