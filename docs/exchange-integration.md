# Exchange Integration
- [Exchange Integration](#exchange-integration)
  * [Use Public Services](#use-public-services)
    + [REST API](#rest-api)
    + [Node RPC](#node-rpc)
  * [Run your own full node](#run-your-own-full-node)
  * [Access via Node Command Line Interface (CLI)](#access-via-node-command-line-interface--cli-)
  * [Use SDKs](#use-sdks)


## Use Public Services 

There are some public nodes running by Binance Chain community which allows you to interact with the blockchain. There are two ways:
### REST API 
 Here is a list of all the Rest API information it provides: <https://docs.binance.org/api-reference/dex-api/paths.html> 
### Node RPC
Here is a list of all the Node RPC services it provides: <https://docs.binance.org/api-reference/node-rpc.html> 


## Run your own full node

Running a full node requires a much more technical resources, and you need to allocate more hardware/bandwidth resources. 
Please refer to this guide about [how to run your own node](fullnode.md).

## Access via Node Command Line Interface (CLI)

A Command Line Interface is available for Linux and Mac platforms. Please refer to the
[CLI Reference](api-reference/cli.md).

## Use SDKs
There are two advanced sdk solutions for Binance chain: [Java](<https://github.com/binance-chain/java-sdk>) and [Golang](<https://github.com/binance-chain/go-sdk>). Both solutions provide functions for:
* Create wallets and manage keys
* Encode/sign transactions and submit to Binance Chain/DEX, including Transfer, New Order, Cancel Order, etc.
* Communicate with Binance Chain/DEX Node RPC calls  through public node RPC services or your own private full nodes

Please refer to its documents for more informations:

* <https://github.com/binance-chain/go-sdk/wiki>
* <https://github.com/binance-chain/java-sdk/wiki>
