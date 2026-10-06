## MetalTools

> `/System/Library/PrivateFrameworks/MetalTools.framework/MetalTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x354d7` | `0x3550d` | **`+0x36`** |
| `__TEXT.__text` | `0x1463ac` | `0x1463dc` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0xf700` | `0xf720` | **`+0x20`** |

### Other Changes

```diff

-382.5.0.0.0
+382.5.3.0.0

-  CStrings:  3686
+  CStrings:  3687
Functions:
~ -[MTLDebugDevice tensorSizeAndAlignWithDescriptor:] : 288 -> 336
CStrings:
+ "descriptor should not configure any auxiliary planes."
```
