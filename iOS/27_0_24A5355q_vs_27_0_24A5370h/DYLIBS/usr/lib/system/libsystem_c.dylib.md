## libsystem_c.dylib

> `/usr/lib/system/libsystem_c.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x790b4` | `0x798d0` | **`+0x81c`** |
| `__TEXT.__const` | `0x26d0` | `0x27a0` | **`+0xd0`** |
| `__DATA_CONST.__const` | `0x18f0` | `0x1910` | **`+0x20`** |
| `__TEXT.__cstring` | `0x3273` | `0x3280` | **`+0xd`** |
| `__AUTH_CONST.__auth_got` | `0x808` | `0x810` | **`+0x8`** |

### Other Changes

```diff

-1782.0.0.0.0
+1786.0.0.0.0

-  Functions: 1875
-  Symbols:   2372
-  CStrings:  881
+  Functions: 1877
+  Symbols:   2377
+  CStrings:  884
Symbols:
+ _filter_utmpx
+ _getpwnam_r
+ _putpair
+ _safechar
+ _ufslike_filesystems
CStrings:
+ "apfs"
+ "hfs"
+ "nfs"
```
