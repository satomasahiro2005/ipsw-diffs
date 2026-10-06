## PhotosFileProvider

> `/System/Library/ExtensionKit/Extensions/PhotosFileProvider.appex/PhotosFileProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27ac` | `0x29f0` | **`+0x244`** |
| `__DATA_CONST.__cfstring` | `0x300` | `0x2e0` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0x320` | `0x340` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xaa0` | `0xac0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0xa7e` | `0xa9b` | **`+0x1d`** |
| `__TEXT.__cstring` | `0x296` | `0x27b` | **`-0x1b`** |
| `__DATA_CONST.__got` | `0x110` | `0x128` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x198` | `0x1a8` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x2d8` | `0x2e0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-910.27.103.0.0
+910.33.102.0.0

-  Functions: 27
-  Symbols:   94
+  Functions: 28
+  Symbols:   99
Symbols:
+ _NSCocoaErrorDomain
+ _OBJC_CLASS_$_NSMutableDictionary
+ _PHErrorCodeIsPublic
+ _PHPhotosErrorDomain
+ _PLHasInternalDiagnostics
CStrings:
+ "setObject:forKeyedSubscript:"
- "PFPAssetRequestErrorDomain"
```
