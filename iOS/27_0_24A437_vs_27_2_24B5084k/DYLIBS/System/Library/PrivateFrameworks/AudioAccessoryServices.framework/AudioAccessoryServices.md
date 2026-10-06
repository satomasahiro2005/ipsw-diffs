## AudioAccessoryServices

> `/System/Library/PrivateFrameworks/AudioAccessoryServices.framework/AudioAccessoryServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x50950` | `0x508bc` | **`-0x94`** |
| `__AUTH_CONST.__cfstring` | `0x2b60` | `0x2b40` | **`-0x20`** |
| `__TEXT.__cstring` | `0xf3e1` | `0xf3d5` | **`-0xc`** |

### Other Changes

```diff

-40.41.1.1.10
+41.4.0.0.0

-  CStrings:  2016
+  CStrings:  2015
Functions:
~ +[AAAssetHelper bluetoothProductIDToVideoAsset:withColor:isCase:] : 384 -> 260
~ +[AAAssetHelper productColorAssetExists:withColor:] : 392 -> 368
CStrings:
- "%@-Seed-mov"
```
