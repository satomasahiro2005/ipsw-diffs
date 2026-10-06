## ACCNowPlayingFeature

> `/System/Library/PrivateFrameworks/CoreAccessoriesFeatures.framework/XPCServices/ACCNowPlayingFeature.xpc/ACCNowPlayingFeature`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12a28` | `0x1291c` | **`-0x10c`** |
| `__TEXT.__objc_stubs` | `0x2260` | `0x2200` | **`-0x60`** |
| `__TEXT.__objc_methname` | `0x2b5b` | `0x2afc` | **`-0x5f`** |
| `__DATA.__objc_const` | `0x22a0` | `0x2270` | **`-0x30`** |
| `__DATA.__objc_selrefs` | `0xab8` | `0xa98` | **`-0x20`** |
| `__DATA_CONST.__cfstring` | `0xc80` | `0xc60` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x1010` | `0xff8` | **`-0x18`** |
| `__TEXT.__cstring` | `0x1213` | `0x11fe` | **`-0x15`** |
| `__DATA_CONST.__got` | `0x268` | `0x260` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x440` | `0x438` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x13c` | `0x138` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1203.0.0.0.0
+1210.0.0.502.1

-  Functions: 435
-  Symbols:   1304
-  CStrings:  905
+  Functions: 433
+  Symbols:   1296
+  CStrings:  899
Symbols:
- -[MediaLibraryHelper _updateITunesRadioEnabled]
- -[MediaLibraryHelper iTunesRadioEnabled]
- OBJC_IVAR_$_MediaLibraryHelper._iTunesRadioEnabled
- _OBJC_CLASS_$_MPRadioLibrary
- __iTunesRadioEnabledOverride.__overrideRadioAvailable
- _objc_msgSend$_updateITunesRadioEnabled
- _objc_msgSend$defaultRadioLibrary
- _objc_msgSend$isEnabled
CStrings:
- "_iTunesRadioEnabled"
- "_updateITunesRadioEnabled"
- "defaultRadioLibrary"
- "iTunesRadioEnabled"
- "isEnabled"
- "overrideRadioEnabled"
```
