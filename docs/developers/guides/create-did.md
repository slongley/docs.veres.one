# Creating a DID on Veres One

This quick Developer Guide will walk you through creating a decentralized
identifier using command line tools.

## Requirements

* [Node v8.9+](https://nodejs.org/en/download/)

## Install did-client

Install the Decentralized Identifier client by running the following command:

```
> mkdir did-client
> cd did-client
> npm install did-client
```

## Create a Decentralized Identifier

Create a Decentralized Identifier on the Veres One Testnet by running the
following command:

```
> ./node_modules/did-client/did create
```

Once the command above runs, you will have a new Decentralized Identifier.
Information related to your Decentralized Identifier will be stored in the
following directory:

```
> ls $HOME/.did/
```
