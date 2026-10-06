## PhotosMessagesApp

> `/System/Library/ExtensionKit/Extensions/PhotosMessagesApp.appex/PhotosMessagesApp`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5304` | `0x5630` | **`+0x32c`** |
| `__DATA_CONST.__cfstring` | `0x2e0` | `0x3c0` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x418` | `0x4b9` | **`+0xa1`** |
| `__TEXT.__objc_methname` | `0x1dcc` | `0x1e52` | **`+0x86`** |
| `__TEXT.__objc_stubs` | `0x1ce0` | `0x1d60` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x5d0` | `0x638` | **`+0x68`** |
| `__TEXT.__auth_stubs` | `0x4a0` | `0x4d0` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x8d8` | `0x8f8` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x260` | `0x278` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x4ac` | `0x4bc` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1f8` | `0x200` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-912.0.234.0.0
+912.0.235.0.0

-  Functions: 96
-  Symbols:   139
-  CStrings:  449
+  Functions: 100
+  Symbols:   142
+  CStrings:  461
Symbols:
+ _PUProvenanceAssetsContainSensitiveEdits
+ _PXExists
+ _objc_retain_x28
CStrings:
+ ""
+ "B16@?0@\"PHAsset\"8"
+ "CANCEL"
+ "PROVENANCE_SHARE_CONTINUE_ACTION"
+ "PROVENANCE_SHARE_EDIT_WARNING_MESSAGE"
+ "PROVENANCE_SHARE_EDIT_WARNING_TITLE"
+ "PhotosUI"
+ "PhotosUIProvenance"
+ "_confirmProvenanceSensitiveEdits:completionHandler:"
+ "localizedStringForKey:value:table:"
+ "pu_PhotosUIFrameworkBundle"
+ "setPreferredAction:"
```
