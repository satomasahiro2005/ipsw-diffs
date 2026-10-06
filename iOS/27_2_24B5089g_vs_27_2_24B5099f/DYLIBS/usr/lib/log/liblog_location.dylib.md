## liblog_location.dylib

> `/usr/lib/log/liblog_location.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x48d0` | `0x4908` | **`+0x38`** |
| `__AUTH_CONST.__cfstring` | `0x5580` | `0x55a0` | **`+0x20`** |
| `__DATA.__data` | `0x920` | `0x930` | **`+0x10`** |
| `__DATA_CONST.__const` | `0xae8` | `0xaf0` | **`+0x8`** |

### Other Changes

```diff

-3186.0.17.0.1
+3186.0.21.0.0

-  Symbols:   456
-  CStrings:  691
+  Symbols:   458
+  CStrings:  692
Symbols:
+ _logObject_MemoryPressure_Default
+ _onceToken_MemoryPressure_Default
CStrings:
+ "CLLocationProvider_Type::kNotificationBufferedGnssLeech"
```
