## EmbeddedDataReset

> `/System/Library/PrivateFrameworks/EmbeddedDataReset.framework/EmbeddedDataReset`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x224c` | `0x228c` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x830` | `0x860` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x180` | `0x1a0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x45c` | `0x474` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x318` | `0x328` | **`+0x10`** |
| `__TEXT.__cstring` | `0x277` | `0x287` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x44` | `0x48` | **`+0x4`** |

### Other Changes

```diff

-2027.0.1.0.0
+2027.1.1.0.0

-  Functions: 67
-  Symbols:   232
-  CStrings:  49
+  Functions: 69
+  Symbols:   235
+  CStrings:  50
Symbols:
+ -[DDRResetOptions sanitizeStorage]
+ -[DDRResetOptions setSanitizeStorage:]
+ _OBJC_IVAR_$_DDRResetOptions._sanitizeStorage
CStrings:
+ "sanitizeStorage"
```
