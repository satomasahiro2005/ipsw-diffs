## SoftwareUpdateUIFoundation

> `/System/Library/PrivateFrameworks/SoftwareUpdateUIFoundation.framework/SoftwareUpdateUIFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa2d78` | `0xa2ff0` | **`+0x278`** |
| `__AUTH_CONST.__cfstring` | `0x3b20` | `0x3b80` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x2250` | `0x22a8` | **`+0x58`** |
| `__TEXT.__cstring` | `0x65de` | `0x660e` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x1750` | `0x1770` | **`+0x20`** |
| `__DATA.__data` | `0xdd0` | `0xdf0` | **`+0x20`** |
| `__DATA.__bss` | `0x35f8` | `0x3608` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1110` | `0x1120` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1358` | `0x1360` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x1f6c` | `0x1f74` | **`+0x8`** |

### Other Changes

```diff

-772.0.0.0.0
+772.0.3.0.0

-  Functions: 1985
-  Symbols:   2121
-  CStrings:  902
+  Functions: 1990
+  Symbols:   2128
+  CStrings:  905
Symbols:
+ +[SUUILoggingContext testsLogger]
+ _MA_KNOX_URL_OVERRIDE_DEFAULT_KEY
+ _MA_WKMS_URL_OVERRIDE_DEFAULT_KEY
+ ___33+[SUUILoggingContext testsLogger]_block_invoke
+ _kSUUILoggerKeysTests
+ _testsLogger.logger
+ _testsLogger.loggerOnce
CStrings:
+ "KnoxURLOverride"
+ "Tests"
+ "WKMSURLOverride"
```
