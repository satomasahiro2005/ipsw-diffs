## libnfshared.dylib

> `/usr/lib/libnfshared.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x5a0` | `0x550` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x5f0` | `0x640` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x4760` | `0x4740` | **`-0x20`** |
| `__TEXT.__cstring` | `0x4ccd` | `0x4cb7` | **`-0x16`** |
| `__TEXT.__text` | `0x24ac4` | `0x24ab4` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x6e8` | `0x6f8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1d0` | `0x1c8` | **`-0x8`** |

### Other Changes

```diff

-370.37.0.0.0
+370.38.2.0.0

-  Symbols:   404
-  CStrings:  944
+  Symbols:   403
+  CStrings:  943
Symbols:
- __os_log_default
CStrings:
+ "nfccFWVersion"
- "isDevTestMode"
- "startOnLocationUpdate"
```
