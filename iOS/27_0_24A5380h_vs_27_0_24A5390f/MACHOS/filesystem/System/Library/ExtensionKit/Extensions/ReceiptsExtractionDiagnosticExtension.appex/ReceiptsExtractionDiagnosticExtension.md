## ReceiptsExtractionDiagnosticExtension

> `/System/Library/ExtensionKit/Extensions/ReceiptsExtractionDiagnosticExtension.appex/ReceiptsExtractionDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7c78` | `0x8124` | **`+0x4ac`** |
| `__TEXT.__objc_stubs` | `0x4c0` | `0x580` | **`+0xc0`** |
| `__TEXT.__const` | `0x312` | `0x38a` | **`+0x78`** |
| `__TEXT.__objc_methname` | `0x3d1` | `0x445` | **`+0x74`** |
| `__DATA.__objc_selrefs` | `0x150` | `0x180` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x980` | `0x9b0` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x4c8` | `0x4e0` | **`+0x18`** |
| `__DATA.__bss` | `0x48` | `0x58` | **`+0x10`** |
| `__DATA.__data` | `0xe0` | `0xf0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xe0` | `0xf0` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x12f` | `0x139` | **`+0xa`** |
| `__TEXT.__unwind_info` | `0x1a8` | `0x1a0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-365.0.0.0.0
+366.1.0.0.0

+  - /System/Library/Frameworks/Photos.framework/Photos

-  Functions: 86
-  Symbols:   112
-  CStrings:  74
+  Functions: 94
+  Symbols:   114
+  CStrings:  80
Symbols:
+ _OBJC_CLASS_$_PHAsset
+ _OBJC_CLASS_$_PHAssetResource
+ _objc_retain_x23
- _swift_release_x27
CStrings:
+ "assetResourcesForAsset:"
+ "fetchAssetsWithLocalIdentifiers:options:"
+ "firstObject"
+ "originalFilename"
+ "setCreationDate:"
+ "type"
```
