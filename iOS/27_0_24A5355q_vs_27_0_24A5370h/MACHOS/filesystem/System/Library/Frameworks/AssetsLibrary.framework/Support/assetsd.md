## assetsd

> `/System/Library/Frameworks/AssetsLibrary.framework/Support/assetsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17f4c` | `0x17fec` | **`+0xa0`** |
| `__TEXT.__objc_stubs` | `0x49c0` | `0x4a00` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x5494` | `0x54c7` | **`+0x33`** |
| `__TEXT.__oslogstring` | `0x3f73` | `0x3fa6` | **`+0x33`** |
| `__DATA.__objc_selrefs` | `0x1440` | `0x1450` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0xb20` | `0xb30` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x5a0` | `0x5a8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x538` | `0x540` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0

-  Symbols:   414
-  CStrings:  1238
+  Symbols:   415
+  CStrings:  1241
Symbols:
+ _PLSearchBackendIndexingEngineGetLog
CStrings:
+ "libraryStatsForPhotoLibrary:error:"
+ "maskForHighPrioritySearchIndexing"
+ "prepareForProcessTermination"
+ "signaling search indexing needed for locale change"
- "libraryStatsWithCPLManager:photoLibrary:error:"
```
