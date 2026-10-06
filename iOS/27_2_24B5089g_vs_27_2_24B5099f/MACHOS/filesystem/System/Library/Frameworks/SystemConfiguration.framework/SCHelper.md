## SCHelper

> `/System/Library/Frameworks/SystemConfiguration.framework/SCHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4bb8` | `0x4db0` | **`+0x1f8`** |
| `__TEXT.__oslogstring` | `0x4d7` | `0x505` | **`+0x2e`** |
| `__TEXT.__auth_stubs` | `0x740` | `0x760` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x3a0` | `0x3b0` | **`+0x10`** |
| `__TEXT.__const` | `0xa0` | `0xb0` | **`+0x10`** |
| `__TEXT.__cstring` | `0x3b6` | `0x3bd` | **`+0x7`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1453.0.0.0.0
+1453.40.1.0.0

-  Symbols:   134
-  CStrings:  100
+  Symbols:   136
+  CStrings:  102
Symbols:
+ _close
+ _fdopen
+ _mkstemps
- _fopen
Functions:
~ sub_100004fd4 : 492 -> 996
CStrings:
+ "/Library/Logs/CrashReporter/SCHelper-%4d-%02d-%02d-%02d%02d%02d-XXXXXX.log"
+ "fdopen(%s) failed: %s"
+ "mkstemps(%s) failed: %s"
- "/Library/Logs/CrashReporter/SCHelper-%4d-%02d-%02d-%02d%02d%02d.log"
```
