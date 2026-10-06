## TCC

> `/System/Library/PrivateFrameworks/TCC.framework/TCC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x16c0` | `0x1700` | **`+0x40`** |
| `__TEXT.__cstring` | `0x3338` | `0x336e` | **`+0x36`** |
| `__TEXT.__text` | `0x15aa4` | `0x15a84` | **`-0x20`** |
| `__DATA.__data` | `0x948` | `0x958` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x600` | `0x610` | **`+0x10`** |

### Other Changes

```diff

-903.0.0.0.0
+906.0.0.0.0

-  Symbols:   955
-  CStrings:  603
+  Symbols:   957
+  CStrings:  605
Symbols:
+ _kTCCServiceHealthAccessReminder
+ _kTCCServiceSiriAccess
CStrings:
+ "kTCCServiceHealthAccessReminder"
+ "kTCCServiceSiriAccess"
```
