# ots-open-currency-integration-sdk

## Summary

Cryptocurrencies come in many forms and provide their own "nodes" to interact with their given networks. While they implementations often provide similar functionalities, their exact process for completing transactions may be significantly different. In addition to this, there are many tasks involved with maintaining each of these nodes. Updating protocol versions, handling API changes, and more can become cumbersome and difficult to keep up with as the technological landscape shifts in a quickly evolving industry.

This Technology Specification aims to provide a way to provide a common infrastructure that can be shared and utilized by exchanges and wallets securely and reliably. A commmon implementation that has been reviewed and validated across both the community and those implementing the solutions allow for a common and validated implementation of these currencies and improves the overall User Experience for the user, developers, and exchange/wallet creators.

### Core Concepts

* Integration never receives or maintains private keys.
* 2-Way encrypted communication with signing agent.
* Common request/callback formatting for transactions.
* Containerized output that can be deployed in most environments securely.
* Restricted network output to only the necessary ports and destinations as-defined by the currencies specification.
* Signing agent to handle formatting and signing of transactions.

### Open Discussion Points

* 2-Way Protocol? [MQTT](http://mqtt.org/)? TCP? [FIX](https://www.fixtrading.org/standards/)?
* List of required requests and their responses (schema)
* Data encoding... [Cap'n Proto](https://capnproto.org/)? [Protobuf](https://developers.google.com/protocol-buffers/)?
* Minimum requirements for node integration? Expectations and assumptions that we will make for all implementations?
* Implementation review process?
* Installation process? git? centralized repo? both?
* Handling of tokens for platforms such as Ethereum, NEO, EOS, etc.
* Handling of environment security.
* Kubernetes implementation for coordinating clusters of coins integrated with the CIS.

### Technology Stack

#### Docker

#### Cap'n Proto

#### MQTT
