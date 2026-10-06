## BookLibraryCore

> `/System/Library/PrivateFrameworks/BookLibraryCore.framework/BookLibraryCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x5eee` | `0x60ec` | **`+0x1fe`** |
| `__TEXT.__text` | `0x55268` | `0x55404` | **`+0x19c`** |
| `__TEXT.__const` | `0x1d0` | `0x1d8` | **`+0x8`** |

### Other Changes

```diff

-2310.0.0.0.0
+2353.0.0.0.0

-  CStrings:  1531
+  CStrings:  1534
Functions:
~ sub_25638f334 -> sub_25a2f8334 : 1092 -> 1504
CStrings:
+ "[BLJaliscoServerSource][workaround_18397698] Destroyed database persistentstoreID:%{public}@ storeCount:%lu"
+ "[BLJaliscoServerSource][workaround_18397698] Destroying duplicated database. allCount:%ld distinctCount:%ld storeCount:%lu"
+ "[BLJaliscoServerSource][workaround_18397698] Failed to delete database persistentstoreID:%{public}@ storeCount:%lu %@"
+ "[BLJaliscoServerSource][workaround_18397698] Failed to fetch all items count:  %@"
+ "[BLJaliscoServerSource][workaround_18397698] Failed to fetch distinct items count:  %@"
+ "[BLJaliscoServerSource][workaround_18397698] Skipping store with nil URL persistentstoreID:%{public}@"
- "Failed to delete database:  %@"
- "Failed to fetch all items count:  %@"
- "Failed to fetch distinct items count:  %@"
```
