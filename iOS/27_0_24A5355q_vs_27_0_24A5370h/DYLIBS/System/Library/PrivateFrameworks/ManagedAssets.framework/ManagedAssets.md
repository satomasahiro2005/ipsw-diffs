## ManagedAssets

> `/System/Library/PrivateFrameworks/ManagedAssets.framework/ManagedAssets`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x267b0` | `0x267c4` | **`+0x14`** |

### Other Changes

```text
Functions:
~ ___57-[ManagedAssetsClient(Profile) getAllProfilesWith:error:]_block_invoke_2 : 168 -> 164
~ -[ManagedAssetsClient(Profile) writeV2BlobWith:optype:payload:profileType:error:] : 1176 -> 1212
~ -[ManagedAssetsClient(Profile) parseV2BlobPayload:error:] : 372 -> 392
~ -[ManagedAssetsClient(Profile) importCorePrescription:profile:error:] : 732 -> 728
~ _MAVerifySerializedAssetBlob : 360 -> 380
~ _createFieldsArray : 484 -> 480
~ _convertUpdateInput : 796 -> 788
~ _convertChainedKVQueryOutput : 936 -> 932
~ ___79-[ManagedAssetsClient(FileAsset) openFile:mode:attributes:attributesOut:error:]_block_invoke.38 : 180 -> 176
~ -[MASDSerializedAssets dictionaryRepresentation] : 464 -> 460
~ -[MASDSerializedAssets writeTo:] : 300 -> 296
~ -[MASDSerializedAssets copyWithZone:] : 340 -> 336
~ -[MASDSerializedAssets mergeFrom:] : 304 -> 300
~ -[MASDAssetDescriptor initDescriptorWithOptions:withData:error:] : 1292 -> 1288
~ -[ManagedAssetsClient removeNotificationObserverPointer:observerType:] : 200 -> 196
~ ___52-[ManagedAssetsClient recoveryTaskWhenDaemonIsReady]_block_invoke : 700 -> 696
```
