title: Section Index

# Algorand Networks
Find information about each of Algorand's public networks, including the genesis hash and ID, the current software version, and dispenser information for TestNet and BetaNet.

[Overview](./algorand-networks/index.md) - Landing page with overview of the three networks.

[MainNet](./algorand-networks/mainnet.md) - [TestNet](./algorand-networks/testnet.md) - [BetaNet](./algorand-networks/betanet.md) 🔷

# Command Line Interface Tools (CLI Tools)
List of available commands for three official Algorand CLIs that are included as part of node install packages.

[goal](./cli/goal/goal) - [kmd](./cli/kmd/kmd) - [algokey](./cli/algokey/algokey)

# SDKs

Overview, installation guides, and documentation for the four Algorand SDKs. Also includes a migration guide for developers moving from algod v1 to v2 (recommended).

[SDKs Overview](sdks/index.md)

[JavaScript](sdks/index.md#javascript) - [Python](sdks/index.md#python) - [Java](sdks/index.md#java) - [Go](sdks/index.md#go) 

[V2 Migration Guide](./sdks/migration.md) 🆕

# REST APIs

List of available paths and models for **algod**, **kmd**, and **indexer**.

[algod v2](./rest-apis/algod/v2.md) 🆕 - [algod v1](./rest-apis/algod/v1.md) - [kmd](./rest-apis/kmd.md) - [indexer](./rest-apis/indexer.md) 🆕

# Smart Contracts (TEAL)

The language specification, a list of available opcodes, and guidelines for use of the Transaction Execution Approval Language (TEAL). Also includes templates, with walkthrough explanations, to solve several common use cases written in TEAL.

[TEAL Specification](./teal/specification.md) - [TEAL Opcodes](./teal/opcodes.md) - [TEAL Guidelines](./teal/guidelines.md)


[Delegate Key Registration Template](./teal/templates/delegate_keyreg.md) - [Dynamic Fee Template](./teal/templates/dynamic_fee.md) - [Hash Time Lock Contract Template](./teal/templates/htlc.md) - [Limit Order (Contract Owner Has Algos) Template](./teal/templates/limit_ordera.md) - [Split Template](./teal/templates/split.md)

# Transaction Reference

An index of the structure and fields of Algorand Transactions.

[Common Fields](./transactions.md#common-fields) - [Payment](transactions.md#payment-transaction) - [Key Registration](transactions.md#key-registration-transaction) - [Asset Configuration](./transactions.md#asset-configuration-transaction) - [Asset Transfer](./transactions.md#asset-transfer-transaction) - [Asset Opt-In](./transactions.md#asset-accept-transaction) - [Asset Clawback](./transactions.md#asset-clawback-transaction) - [Asset Freeze](./transactions.md#asset-freeze-transaction) - [Application Call](./transactions.md#application-call-transaction) - [Signed](./transactions.md#signed-transaction)

# Payment Prompts

The [URI specification](payment_prompts.md) representing a standardized way for applications and websites to send requests and information through deeplinks, QR codes, etc. 

# WalletConnect Schema

The [WalletConnect Schema](./walletconnect-schema.md) is a set of JSON-RPC 2.0 requests and responses supporting secure communication between mobile wallets and decentralized applications.

# Node Reference

An overview of the files and software packaged with a node plus the full list of node configuration settings.

- [Node Artifacts](./node/artifacts.md) 
- [Node Configuration Settings](./node/config.md) 
- [Configure Node as a Relay](./node/relay.md)

# Parameters and Constraints

Includes tables describing frequently used [chain parameters and constraints](./parameter_tables.md).