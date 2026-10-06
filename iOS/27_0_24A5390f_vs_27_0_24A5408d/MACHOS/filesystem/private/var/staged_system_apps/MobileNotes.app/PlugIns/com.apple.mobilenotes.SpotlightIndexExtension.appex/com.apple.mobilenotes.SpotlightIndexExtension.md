## com.apple.mobilenotes.SpotlightIndexExtension

> `/private/var/staged_system_apps/MobileNotes.app/PlugIns/com.apple.mobilenotes.SpotlightIndexExtension.appex/com.apple.mobilenotes.SpotlightIndexExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4e00` | `0x4f28` | **`+0x128`** |
| `__TEXT.__oslogstring` | `0x4a1` | `0x50e` | **`+0x6d`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2998.0.0.0.0
+3001.2.1.0.0

-  Functions: 131
+  Functions: 132

-  CStrings:  176
+  CStrings:  177
CStrings:
+ "Index extension wants to reindex specific items but in-extension indexing is disabled. Deferring to the app."
+ "reindexSearchableItemsWithObjectIDURIs:scope:completionHandler:"
- "reindexSearchableItemsWithObjectIDURIs:completionHandler:"
```
