## CoreDuet

> `/System/Library/PrivateFrameworks/CoreDuet.framework/CoreDuet`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x15c4a` | `0x15cd7` | **`+0x8d`** |
| `__TEXT.__text` | `0x18f77c` | `0x18f800` | **`+0x84`** |
| `__AUTH_CONST.__cfstring` | `0x12ce0` | `0x12d40` | **`+0x60`** |
| `__AUTH_CONST.__objc_intobj` | `0x2298` | `0x22b0` | **`+0x18`** |

### Other Changes

```diff

-1959.0.1.0.0
+1962.0.1.0.0

-  CStrings:  4647
+  CStrings:  4650
Functions:
~ -[_CDSpotlightItemRecorder runOperation:] : 940 -> 944
~ _OUTLINED_FUNCTION_27 : 12 -> 20
~ ___113-[_CDSpotlightItemRecorder initWithInteractionRecorder:knowledgeStore:rateLimitEnforcer:deletionManagerOverride:]_block_invoke.652 : 660 -> 664
~ -[_CDSpotlightItemRecorder _deleteUserActivitiesWithPersistentIdentifiers:bundleID:] : 884 -> 888
~ ___83-[_CDSpotlightItemRecorder deleteSearchableItemsSinceDate:bundleID:withCompletion:]_block_invoke : 344 -> 388
~ ___81-[_CDSpotlightItemRecorder deleteAllItemsWithBundleID:isCSSIDeletion:completion:]_block_invoke : 92 -> 160
CStrings:
+ "deleteAllItemsWithBundleID (excluding sharesheet)"
+ "mechanism != %@ AND mechanism != %@"
+ "mechanism != %@ AND mechanism != %@ AND bundleId == %@"
```
