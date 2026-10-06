## Dyld

> `/System/Library/PrivateFrameworks/Dyld.framework/Dyld`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x51e98` | `0x51fc0` | **`+0x128`** |
| `__AUTH_CONST.__auth_got` | `0xb68` | `0xb70` | **`+0x8`** |
| `__DATA.__common` | `0x60` | `0x68` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x11f8` | `0x1200` | **`+0x8`** |

### Other Changes

```diff

-27062.0.0.0.0
+27102.0.0.0.0

-  Functions: 1459
-  Symbols:   1054
+  Functions: 1461
+  Symbols:   1056
Symbols:
+ _gWithActiveAtlas
+ _malloc
```
