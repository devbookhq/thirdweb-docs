---
slug: /sdk.nftcontractdeploymetadata
title: NFTContractDeployMetadata interface
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## NFTContractDeployMetadata interface

Options for deploying an NFT contract

**Signature:**

```typescript
export interface NFTContractDeployMetadata
```

## Properties

| Property                                                                                   | Modifiers | Type               | Description                                                                                   |
| ------------------------------------------------------------------------------------------ | --------- | ------------------ | --------------------------------------------------------------------------------------------- |
| [description?](./sdk.nftcontractdeploymetadata.description.md)                             |           | string             | <i>(Optional)</i> Optional description of the contract                                        |
| [external_link?](./sdk.nftcontractdeploymetadata.external_link.md)                         |           | string             | <i>(Optional)</i> Optional url for the contract                                               |
| [fee_recipient?](./sdk.nftcontractdeploymetadata.fee_recipient.md)                         |           | string             | <i>(Optional)</i> The address that will receive the proceeds from secondary sales (royalties) |
| [image?](./sdk.nftcontractdeploymetadata.image.md)                                         |           | FileBufferOrString | <i>(Optional)</i> Optional image for the contract                                             |
| [name](./sdk.nftcontractdeploymetadata.name.md)                                            |           | string             | name of the contract                                                                          |
| [platform_fee_basis_points?](./sdk.nftcontractdeploymetadata.platform_fee_basis_points.md) |           | number             | <i>(Optional)</i> The percentage (in basis points) of platform fees                           |
| [platform_fee_recipient?](./sdk.nftcontractdeploymetadata.platform_fee_recipient.md)       |           | string             | <i>(Optional)</i> The address that will receive the proceeds from platform fees               |
| [primary_sale_recipient](./sdk.nftcontractdeploymetadata.primary_sale_recipient.md)        |           | string             | The address that will receive the proceeds from primary sales                                 |
| [seller_fee_basis_points?](./sdk.nftcontractdeploymetadata.seller_fee_basis_points.md)     |           | number             | <i>(Optional)</i> The percentage (in basis points) of royalties for secondary sales           |
| [symbol?](./sdk.nftcontractdeploymetadata.symbol.md)                                       |           | string             | <i>(Optional)</i> Symbol for the NFTs                                                         |
| [trusted_forwarders?](./sdk.nftcontractdeploymetadata.trusted_forwarders.md)               |           | string\[\]         | <i>(Optional)</i> Custom gasless trusted forwarder addresses                                  |
