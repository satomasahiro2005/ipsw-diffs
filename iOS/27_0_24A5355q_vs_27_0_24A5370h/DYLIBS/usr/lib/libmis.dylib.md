## libmis.dylib

> `/usr/lib/libmis.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c300` | `0x3c71c` | **`+0x41c`** |
| `__AUTH_CONST.__cfstring` | `0x1cc0` | `0x1d20` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x1458` | `0x14b8` | **`+0x60`** |
| `__TEXT.__cstring` | `0x530f` | `0x5351` | **`+0x42`** |
| `__TEXT.__oslogstring` | `0x30b5` | `0x30f0` | **`+0x3b`** |
| `__DATA.__bss` | `0xc50` | `0xc80` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0xf00` | `0xf10` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x4708` | `0x4710` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x2e0` | `0x2e8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xe70` | `0xe68` | **`-0x8`** |
| `__TEXT.__gcc_except_tab` | `0x31c` | `0x320` | **`+0x4`** |

### Other Changes

```diff

-486.0.0.0.0
+487.0.0.0.0

-  Functions: 1213
-  Symbols:   1017
-  CStrings:  689
+  Functions: 1217
+  Symbols:   1021
+  CStrings:  693
Symbols:
+ _CFPreferencesCopyValue
+ _CTParseLeafSPKI
+ _kCFPreferencesAnyHost
+ _objc_retain_x27
CStrings:
+ "1cf29dc4-4f08-457d-b9a7-512c89f0e142"
+ "Overriding expiry for profile %{public}@ with timestamp %f"
+ "mobile"
+ "relaxProfileExpiry-%@"
```
