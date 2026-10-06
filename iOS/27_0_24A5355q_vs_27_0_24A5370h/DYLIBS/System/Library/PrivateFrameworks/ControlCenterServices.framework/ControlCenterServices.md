## ControlCenterServices

> `/System/Library/PrivateFrameworks/ControlCenterServices.framework/ControlCenterServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf31c` | `0xf304` | **`-0x18`** |

### Other Changes

```diff

-696.0.1.0.0
+699.0.100.0.0
Functions:
~ -[CCSRemoteServiceProvider enumerateEndpointsUsingBlock:] : 360 -> 356
~ -[CCSModuleRepository _queue_updateAllModuleMetadataForAllModuleMetadata:] : 412 -> 408
~ -[CCSModuleRepository _queue_updateLoadableModuleMetadataForAvailableModuleMetadata:] : 608 -> 604
~ -[CCSModuleRepository _queue_moduleIdentifiersForMetadata:] : 368 -> 364
~ -[CCSModuleRepository _queue_associatedBundleIdentifiersForModuleMetadata:] : 368 -> 364
~ -[CCSModuleRepository _queue_gestaltQuestionsForModuleMetadata:] : 384 -> 380
```
