---
slug: /sdk.erc1155droppable.claim
title: Erc1155Droppable.claim property
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## Erc1155Droppable.claim property

Claim tokens and configure claim conditions

## Example

```javascript
const quantity = 10;
const tokenId = 0;
await contract.edition.drop.claim.to("0x...", 0, quantity);
```

**Signature:**

```typescript
claim: Erc1155Claimable | undefined;
```

## Remarks

Let users claim NFTs. Define who can claim NFTs in the collection, when and how many.
