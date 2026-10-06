## BaseBoardUI

> `/System/Library/PrivateFrameworks/BaseBoardUI.framework/BaseBoardUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18f38` | `0x18fdc` | **`+0xa4`** |
| `__TEXT.__oslogstring` | `0x778` | `0x7b0` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0x2e78` | `0x2ea4` | **`+0x2c`** |
| `__TEXT.__const` | `0x3e0` | `0x3f8` | **`+0x18`** |

### Other Changes

```diff

-827.0.0.0.0
+827.2.1.1.0

-  Symbols:   1319
-  CStrings:  183
+  Symbols:   1321
+  CStrings:  184
Symbols:
+ ___error
+ _strerror_r
Functions:
~ -[BSUIMappedImageCacheRegistry tmpPath] : 1024 -> 1188
CStrings:
+ "BSUIMappedImageCache failed to get relative tmpDir from dirhelper with errno=%i (%{public}s) for %@"
+ "BSUIMappedImageCache is falling back to NSTemporaryDirectory=%@ for %@"
- "BSUIMappedImageCache failed to get relative tmpDir from dirhelper for %@ : falling back to NSTemporaryDirectory=%@"
```
