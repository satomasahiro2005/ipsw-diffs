## NewsAnalyticsUpload

> `/System/Library/PrivateFrameworks/NewsAnalyticsUpload.framework/NewsAnalyticsUpload`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19a80` | `0x19a60` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0x758` | `0x760` | **`+0x8`** |

### Other Changes

```diff

-5916.1.0.0.0
+5920.0.0.0.0

-  Symbols:   879
+  Symbols:   880
Symbols:
+ _swift_release_x26
Functions:
~ -[NDAnalyticsEnvelopeStore _deleteEnvelopesForKeysFromStore:] : 308 -> 304
~ -[NDAnalyticsEnvelopeStore _reportEnvelopesToNewsAutomationIfNeeded:] : 936 -> 940
~ -[NDAnalyticsPayloadUploader uploadPayloadsForInfos:withEnvelopeStore:perPayloadCompletion:completion:] : 688 -> 684
~ ___116-[NDAnalyticsPayloadAssembler determinePayloadDeliveryWindowForEntries:withLastUploadDatesByContentType:completion:]_block_invoke : 892 -> 888
~ ___150-[NDAnalyticsPayloadAssembler assemblePayloadsWithEntries:lastUploadDatesByContentType:droppedEnvelopeReasonsToUpload:envelopeSizeByEntry:completion:]_block_invoke_7 : 1456 -> 1452
~ ___150-[NDAnalyticsPayloadAssembler assemblePayloadsWithEntries:lastUploadDatesByContentType:droppedEnvelopeReasonsToUpload:envelopeSizeByEntry:completion:]_block_invoke_8 : 248 -> 244
~ +[NAUAnalyticsEnvelopeTracker _registerContentTypes:withEventName:] : 540 -> 536
~ sub_28bad05f4 -> sub_28d07d5e0 : 1336 -> 1332
~ sub_28bad2148 -> sub_28d07f130 : 96 -> 88
```
