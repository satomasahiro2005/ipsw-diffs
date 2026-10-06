## MobileAsset

> `/System/Library/PrivateFrameworks/MobileAsset.framework/MobileAsset`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8c5f8` | `0x8c538` | **`-0xc0`** |
| `__AUTH_CONST.__cfstring` | `0xfd40` | `0xfda0` | **`+0x60`** |
| `__TEXT.__cstring` | `0x13a5e` | `0x13ab2` | **`+0x54`** |
| `__TEXT.__unwind_info` | `0x1ef8` | `0x1f20` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x2738` | `0x2750` | **`+0x18`** |

### Other Changes

```diff

-2215.0.0.502.1
+2215.0.4.0.0

-  Symbols:   5018
-  CStrings:  2822
+  Symbols:   5021
+  CStrings:  2825
Symbols:
+ _kMobileAssetPreferencesInProcessSessionMaxConcurrent
+ _kMobileAssetPreferencesPallasSessionMaxConcurrent
+ _kMobileAssetPreferencesSplunkSessionMaxConcurrent
CStrings:
+ "InProcessSessionMaxConcurrent"
+ "PallasSessionMaxConcurrent"
+ "SplunkSessionMaxConcurrent"
```
