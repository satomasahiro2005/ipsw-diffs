## PrototypeTools

> `/System/Library/PrivateFrameworks/PrototypeTools.framework/PrototypeTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18c18` | `0x18ca8` | **`+0x90`** |
| `__AUTH_CONST.__objc_const` | `0x62b8` | `0x62e8` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x1880` | `0x18a0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x24f0` | `0x2510` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1490` | `0x14a8` | **`+0x18`** |
| `__TEXT.__cstring` | `0x1313` | `0x131d` | **`+0xa`** |
| `__DATA.__objc_ivar` | `0x22c` | `0x230` | **`+0x4`** |

### Other Changes

```diff

-164.0.0.0.0
+165.0.0.0.0

-  Functions: 802
-  Symbols:   1583
+  Functions: 805
+  Symbols:   1587
Symbols:
+ -[PTRow infoText:]
+ -[PTRow infoText]
+ -[PTRow setInfoText:]
+ _OBJC_IVAR_$_PTRow._infoText
CStrings:
+ "infoText"
- "\xf1"
```
