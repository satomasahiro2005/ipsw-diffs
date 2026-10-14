## MobileSafari

> `/System/Library/DataClassMigrators/MobileSafari.migrator/MobileSafari`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5d24` | `0x5e74` | **`+0x150`** |
| `__TEXT.__objc_stubs` | `0x14e0` | `0x15a0` | **`+0xc0`** |
| `__TEXT.__objc_methname` | `0x14cc` | `0x158b` | **`+0xbf`** |
| `__DATA.__objc_selrefs` | `0x640` | `0x670` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x440` | `0x450` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x3c0` | `0x3d0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x230` | `0x238` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x2b8` | `0x2c0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7625.2.7.1.0
+7625.2.8.10.4

-  Functions: 113
-  Symbols:   218
-  CStrings:  445
+  Functions: 114
+  Symbols:   220
+  CStrings:  451
Symbols:
+ _OBJC_CLASS_$_SFDeviceUtilities
+ _SFSeedCloudTabsRestorationUUIDIfAbsent
CStrings:
+ "deviceUUID"
+ "isLockedSync"
+ "migratePebblePinnedSuggestionsToBookmarkCollection:"
+ "migratePebblePinnedSuggestionsToBookmarksDatabase"
+ "pebblePinnedSuggestionsFolderIDIfExists"
+ "safariBookmarkCollection"
```
