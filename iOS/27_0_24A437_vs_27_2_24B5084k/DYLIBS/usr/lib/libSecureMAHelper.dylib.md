## libSecureMAHelper.dylib

> `/usr/lib/libSecureMAHelper.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e540` | `0x1e70c` | **`+0x1cc`** |
| `__AUTH_CONST.__auth_got` | `0x688` | `0x680` | **`-0x8`** |
| `__TEXT.__cstring` | `0x6e91` | `0x6e8f` | **`-0x2`** |

### Other Changes

```diff

-2215.0.20.0.0
+2215.40.18.0.0

-  Functions: 431
+  Functions: 432
Symbols:
+ _isDownloadErrorNetworkConnectivityError
- _MAPreferencesIsVerboseLoggingEnabled
Functions:
~ _getPathToAssetWithPurpose : 512 -> 504
~ _isDirStatsEnabledForDirectory : 424 -> 396
+ _isDownloadErrorNetworkConnectivityError
CStrings:
+ "Secure"
- "SecureMA"
```
