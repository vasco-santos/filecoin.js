---
id: filecoin.js.jsonrpcprovider.listmessages
title: JsonRpcProvider.listMessages() method
hide_title: true
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[filecoin.js](./filecoin.js.md) &gt; [JsonRpcProvider](./filecoin.js.jsonrpcprovider.md) &gt; [listMessages](./filecoin.js.jsonrpcprovider.listmessages.md)

## JsonRpcProvider.listMessages() method

looks back and returns all messages with a matching to or from address, stopping at the given height.

<b>Signature:</b>

```typescript
listMessages(filter: {
        To?: string;
        From?: string;
    }, tipSetKey?: TipSetKey, toHeight?: number): Promise<Cid[]>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  filter | { To?: string; From?: string; } |  |
|  tipSetKey | TipSetKey |  |
|  toHeight | number |  |

<b>Returns:</b>

Promise&lt;Cid\[\]&gt;