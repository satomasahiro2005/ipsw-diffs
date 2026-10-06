## Weave

> `/System/Library/PrivateFrameworks/Weave.framework/Weave`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7acc` | `0x7a5c` | **`-0x70`** |

### Other Changes

```text
Functions:
~ _WVGetClassesConformingToProtocol : 204 -> 200
~ -[WVServer _createKeyToProviderMapWithProviders:] : 552 -> 548
~ -[WVServer createSessionIfNeeded] : 852 -> 848
~ ___78-[WVServiceListener initWithDelegate:serviceClasses:enableAnonymousListeners:]_block_invoke : 448 -> 444
~ -[WVPolarisService updateResourcesWithAddedResources:removedResources:] : 616 -> 608
~ _WVGetClassesConformingToProtocolAndImage : 216 -> 212
~ ___43-[WVServer isCurrentServicesContainsClass:]_block_invoke : 276 -> 272
~ -[WVServer _update] : 6956 -> 6900
~ -[WVServer computeInputKeysFromGraphs:] : 808 -> 800
~ -[WVServer computeOutputKeysFromGraphs:] : 1116 -> 1104
~ -[WVServer resourcesRequested:] : 564 -> 560
```
