## Charts

> `/System/Library/Frameworks/Charts.framework/Charts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f17cc` | `0x2f1c30` | **`+0x464`** |
| `__TEXT.__cstring` | `0x2b56` | `0x2c26` | **`+0xd0`** |
| `__DATA.__bss` | `0xa920` | `0xa9a0` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0x10407` | `0x10477` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0x6c98` | `0x6c67` | **`-0x31`** |
| `__TEXT.__const` | `0x3fff8` | `0x40028` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0xbb00` | `0xbae8` | **`-0x18`** |
| `__DATA.__data` | `0x4c90` | `0x4ca0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x71d8` | `0x71e0` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1164` | `0x1168` | **`+0x4`** |

### Other Changes

```diff

-8.0.82.0.0
+8.1.5.0.0

-  Functions: 12747
+  Functions: 12753

-  CStrings:  233
+  CStrings:  234
CStrings:
+ "A non-finite coordinate was encountered while animating chart content, so the affected point is not\ndrawn. Check for NaN or infinite plotted values, or for a plot area that collapsed to zero size."
```
