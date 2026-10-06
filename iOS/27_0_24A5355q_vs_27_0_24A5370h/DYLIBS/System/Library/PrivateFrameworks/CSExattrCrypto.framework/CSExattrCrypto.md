## CSExattrCrypto

> `/System/Library/PrivateFrameworks/CSExattrCrypto.framework/CSExattrCrypto`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8884` | `0x8918` | **`+0x94`** |
| `__TEXT.__const` | `0xd0` | `0x120` | **`+0x50`** |

### Other Changes

```diff

-2444.104.0.0.0
+2448.100.0.0.0
Functions:
~ _MDCopyDecodedXattrFromData : 1136 -> 1148
~ _MDFSOnlyMDCopyXattrsDictionaryForFD : 2112 -> 2108
~ -[MDKeyRing createRandomUUID] : 136 -> 144
~ -[MDKeyRing createRandomAESKey] : 140 -> 148
~ __MDLabelUUIDEncode : 516 -> 424
~ -[_MDLabel updateAttrs:] : 272 -> 280
~ -[MDPrivateXattrServices extractDecryptedDataWith:cryptoCallback:decryptableXids:intoDict:keyRing:xid:] : 1656 -> 1652
~ -[MDPrivateXattrServices copyPrivateXattrsFromData:decryptedXids:] : 888 -> 884
~ _copyUpdatedData : 3704 -> 3680
~ -[MDPrivateXattrServices xidDictWithUUIDs:allKeyUUIDs:] : 484 -> 480
~ -[MDPrivateXattrServices xidDictWithXPCUUIDs:allKeyUUIDs:] : 396 -> 392
~ ___107-[MDPrivateXattrServices updatePrivateXattrParams:flags:forFileDescriptor:mergeCallback:completionHandler:]_block_invoke_2 : 604 -> 600
~ _serializeCFString : 620 -> 628
~ _serializeCFType : 1360 -> 1508
~ _copyCFTypeFromBuffer : 952 -> 960
~ _v2_readVInt32 : 152 -> 160
~ _v2_readVInt64 : 492 -> 572
```
