# bsc-json-rpc-specification
 
# Hyperledger-Besu-json-rpc-specification

[View the Documentation](https://lucasespinosa28.github.io/Hyperledger-Besu-json-rpc-specification/api-documentation/).

## Overview

This repository is the home of the  Hyperledger-Besu [OpenRPC](https://spec.open-rpc.org) document that describes the JSON-RPC basic interface to be implemented by client developers. It contains the tooling and scripts to automate producing artifacts for consuming the JSON-RPC API (docs, clients, etc).

## Fullnode⚠
To use the documentation you need to run a full node

This command will run a full node com basic methods enabled
``docker run  -p 8545:8545 hyperledger/besu:latest --rpc-http-cors-origins=* --rpc-http-enabled=true --network=dev  ``

You want to use method PRIV you'll need to the enable private transaction in your node
[Documentation to enable privacy](https://besu.hyperledger.org/en/stable/Reference/CLI/CLI-Syntax/#privacy-enabled)

## Specification

You can view the specification in documentation form [here](https://lucasespinosa28.github.io/Hyperledger-Besu-json-rpc-specification/api-documentation/) or the raw **OpenRPC Document** [here](openrpc.json).

#### Preview

![eth_rpc_playground_docs_demo_eth_rpc](https://user-images.githubusercontent.com/364566/71375336-ba47f980-2572-11ea-9cd5-38c5149c485a.gif)


## Clients

The clients are generated from the **OpenRPC Document** `openrpc.json` in this repository, and can be used as an alternative to web3.js or ethers.js but for various languages:


## Documentation

[View the Documentation](https://lucasespinosa28.github.io/Hyperledger-Besu-json-rpc-specification/api-documentation/).

### Contributing

Proposals to make method changes should be [made as an issue](https://help.github.com/en/articles/creating-an-issue).

How to contribute, build and release are outlined in [CONTRIBUTING.md](CONTRIBUTING.md), [BUILDING.md](BUILDING.md) and [RELEASING.md](RELEASING.md) respectively. Commits in this repository follow the [CONVENTIONAL_COMMITS.md](CONVENTIONAL_COMMITS.md) specification.

## Resources
- https://besu.hyperledger.org/en/stable/Reference/API-Methods/
