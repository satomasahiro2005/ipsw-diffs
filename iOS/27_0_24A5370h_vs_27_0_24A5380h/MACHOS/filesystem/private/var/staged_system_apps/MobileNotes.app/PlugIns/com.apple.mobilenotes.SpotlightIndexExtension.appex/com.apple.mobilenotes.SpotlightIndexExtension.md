## com.apple.mobilenotes.SpotlightIndexExtension

> `/private/var/staged_system_apps/MobileNotes.app/PlugIns/com.apple.mobilenotes.SpotlightIndexExtension.appex/com.apple.mobilenotes.SpotlightIndexExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4bf4` | `0x4e00` | **`+0x20c`** |
| `__TEXT.__oslogstring` | `0x451` | `0x4a1` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0xbee` | `0xc2e` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x7c0` | `0x800` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x2c0` | `0x2d0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x148` | `0x158` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2991.0.0.0.0
+2996.0.0.0.0

-  Functions: 128
-  Symbols:   143
-  CStrings:  173
+  Functions: 131
+  Symbols:   145
+  CStrings:  176
Symbols:
+ _OBJC_CLASS_$_NSDictionary
+ _kICReindexAttachmentsOnLaunchKey
CStrings:
+ "Error deleting index before notes reindex in extension: %@"
+ "Error reindexing notes in extension: %@"
+ "Index extension did reindex notes; attachments deferred to app"
+ "dictionaryWithObjects:forKeys:count:"
+ "registerDefaults:"
+ "reindexAllSearchableItemsWithScope:completionHandler:"
- "Error reindexing all items in extension: %@"
- "Index extension did reindex all items"
- "reindexAllSearchableItemsWithCompletionHandler:"
```
