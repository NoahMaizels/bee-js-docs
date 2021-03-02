---
id: "utils.eth.isethaddress"
title: "Function: isEthAddress"
sidebar_label: "isEthAddress"
custom_edit_url: null
hide_title: true
---

# Function: isEthAddress

[Utils](../modules/utils.md).[Eth](../modules/utils.eth.md).isEthAddress

▸ **isEthAddress**(`address`: *string* \| [*HexString*](../types/utils.hex.hexstring.md) \| [*HexEthAddress*](../types/utils.eth.hexethaddress.md)): address is BrandedType<string, "HexEthAddress"\>

Check if is valid ethereum address

Pretty much typed version from web3js
https://github.com/ChainSafe/web3.js/blob/1.x/packages/web3-utils/src/utils.js

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`address` | *string* \| [*HexString*](../types/utils.hex.hexstring.md) \| [*HexEthAddress*](../types/utils.eth.hexethaddress.md) | Ethereum address as hex string    |

**Returns:** address is BrandedType<string, "HexEthAddress"\>

True if is valid eth address

Defined in: [bee-js/src/utils/eth.ts:54](https://github.com/ethersphere/bee-js/blob/7dfd556/src/utils/eth.ts#L54)