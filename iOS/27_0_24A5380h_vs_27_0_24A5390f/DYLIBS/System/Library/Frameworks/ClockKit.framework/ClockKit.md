## ClockKit

> `/System/Library/Frameworks/ClockKit.framework/ClockKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6c0e8` | `0x6bf68` | **`-0x180`** |
| `__TEXT.__const` | `0xa78` | `0xb18` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x3d83` | `0x3d43` | **`-0x40`** |
| `__AUTH_CONST.__objc_const` | `0xfbc0` | `0xfbf0` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x97d4` | `0x97e4` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x36a0` | `0x36a8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xb00` | `0xb04` | **`+0x4`** |

### Other Changes

```diff

-2483.503.0.0.0
+2483.512.0.0.0

-  Functions: 3857
-  Symbols:   6845
-  CStrings:  979
+  Functions: 3855
+  Symbols:   6847
+  CStrings:  978
Symbols:
+ -[CLKDevice isSE]
+ GCC_except_table182
+ _OBJC_IVAR_$_CLKDevice._isSE
- GCC_except_table181
CStrings:
- "-[CLKSuperEllipseRectGeometry initForDevice:tangentialInset:]"
```
