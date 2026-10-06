## ShazamKit

> `/System/Library/Frameworks/ShazamKit.framework/ShazamKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa0f2c` | `0xa1578` | **`+0x64c`** |
| `__TEXT.__eh_frame` | `0x2410` | `0x24c0` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0x1401` | `0x1441` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x2138` | `0x2160` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x34b8` | `0x34d8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x850` | `0x860` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x7f8` | `0x7e8` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x314` | `0x324` | **`+0x10`** |
| `__AUTH.__data` | `0x290` | `0x298` | **`+0x8`** |

### Other Changes

```diff

-427.0.36.0.0
+427.0.40.0.0

-  Functions: 3641
+  Functions: 3643

-  CStrings:  574
+  CStrings:  575
CStrings:
+ "Failed to synchronize library after change. Error %@"
```
