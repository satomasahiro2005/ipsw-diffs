## ACCMediaLibraryFeature

> `/System/Library/PrivateFrameworks/CoreAccessoriesFeatures.framework/XPCServices/ACCMediaLibraryFeature.xpc/ACCMediaLibraryFeature`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a520` | `0x2a470` | **`-0xb0`** |
| `__DATA.__objc_const` | `0x3e10` | `0x3de0` | **`-0x30`** |
| `__TEXT.__objc_methname` | `0x5291` | `0x5265` | **`-0x2c`** |
| `__TEXT.__objc_stubs` | `0x4100` | `0x40e0` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x2160` | `0x2150` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x1348` | `0x1340` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x278` | `0x274` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__cstring`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1203.0.0.0.0
+1210.0.0.502.1

-  Functions: 859
-  Symbols:   2118
-  CStrings:  1541
+  Functions: 858
+  Symbols:   2115
+  CStrings:  1539
Symbols:
+ -[ACCMediaLibraryShim _computeRadioEnabled]
+ _objc_msgSend$_computeRadioEnabled
- -[MediaLibraryHelper _updateITunesRadioEnabled]
- -[MediaLibraryHelper iTunesRadioEnabled]
- OBJC_IVAR_$_MediaLibraryHelper._iTunesRadioEnabled
- _objc_msgSend$_updateITunesRadioEnabled
- _objc_msgSend$iTunesRadioEnabled
CStrings:
+ "_computeRadioEnabled"
- "_iTunesRadioEnabled"
- "_updateITunesRadioEnabled"
- "iTunesRadioEnabled"
```
