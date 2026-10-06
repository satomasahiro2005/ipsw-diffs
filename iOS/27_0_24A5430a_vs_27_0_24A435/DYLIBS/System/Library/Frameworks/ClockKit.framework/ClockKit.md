## ClockKit

> `/System/Library/Frameworks/ClockKit.framework/ClockKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6bf68` | `0x6c184` | **`+0x21c`** |
| `__AUTH_CONST.__cfstring` | `0x54c0` | `0x55a0` | **`+0xe0`** |
| `__TEXT.__const` | `0xb18` | `0xba8` | **`+0x90`** |
| `__AUTH_CONST.__objc_intobj` | `0xc78` | `0xcf0` | **`+0x78`** |
| `__AUTH_CONST.__objc_const` | `0xfbf0` | `0xfc50` | **`+0x60`** |
| `__DATA_CONST.__objc_arraydata` | `0x5b8` | `0x608` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x2cfe` | `0x2d47` | **`+0x49`** |
| `__TEXT.__cstring` | `0x3d43` | `0x3d83` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x97e4` | `0x97fc` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x36a8` | `0x36b8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xb04` | `0xb0c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2498` | `0x24a0` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 3855
-  Symbols:   6847
-  CStrings:  978
+  Functions: 3857
+  Symbols:   6851
+  CStrings:  989
Symbols:
+ -[CLKDevice is3]
+ -[CLKDevice isZeusGold]
+ GCC_except_table184
+ _OBJC_IVAR_$_CLKDevice._is3
+ _OBJC_IVAR_$_CLKDevice._isZeusGold
- GCC_except_table182
CStrings:
+ "3"
+ "CLKDevice is3: %u"
+ "CLKDevice isZeusGold: %u"
+ "OVERRIDE 3"
+ "OVERRIDE Zeus Gold"
+ "Watch8,1"
+ "Watch8,2"
+ "Watch8,3"
+ "Watch8,4"
+ "Watch8,5"
+ "ZeusGold"
```
