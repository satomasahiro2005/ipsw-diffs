## MobileAsset

> `/System/Library/PrivateFrameworks/MobileAsset.framework/MobileAsset`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8c538` | `0x8c4f8` | **`-0x40`** |
| `__TEXT.__cstring` | `0x13ab2` | `0x13ae2` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0xfda0` | `0xfdc0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x2750` | `0x2758` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x3810` | `0x3808` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x6d7c` | `0x6d74` | **`-0x8`** |

### Other Changes

```diff

-2215.0.4.0.0
+2215.0.13.0.0

-  Functions: 3067
+  Functions: 3066

-  CStrings:  2825
+  CStrings:  2826
Symbols:
+ _kMobileAssetPreferencesAutoAssetStagerInjectAvailableAlreadyDownloaded
- -[MAAssetDiff initFromInverseOfCategories:]
Functions:
- -[MAAssetDiff initFromInverseOfCategories:]
CStrings:
+ "AutoAssetStagerInjectAvailableAlreadyDownloaded"
```
