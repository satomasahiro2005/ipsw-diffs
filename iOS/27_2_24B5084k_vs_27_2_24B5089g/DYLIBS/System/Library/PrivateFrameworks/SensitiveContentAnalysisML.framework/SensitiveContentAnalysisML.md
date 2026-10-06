## SensitiveContentAnalysisML

> `/System/Library/PrivateFrameworks/SensitiveContentAnalysisML.framework/SensitiveContentAnalysisML`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x1f70` | `0x2710` | **`+0x7a0`** |
| `__AUTH.__data` | `0x4a8` | `—` | **`-0x4a8`** |
| `__AUTH.__objc_data` | `0x320` | `—` | **`-0x320`** |
| `__DATA_DIRTY.__objc_data` | `0x1740` | `0x1a60` | **`+0x320`** |
| `__DATA.__data` | `0x27e8` | `0x24e0` | **`-0x308`** |
| `__TEXT.__text` | `0xf9604` | `0xf967c` | **`+0x78`** |
| `__AUTH_CONST.__objc_const` | `0x5778` | `0x57d8` | **`+0x60`** |
| `__TEXT.__cstring` | `0x3e76` | `0x3ea6` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x1ec4` | `0x1ef4` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x1190` | `0x11a0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x300` | `0x308` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x4534` | `0x453c` | **`+0x8`** |

### Other Changes

```diff

-165.4.0.0.0
+165.5.0.0.0

-  Functions: 6265
-  Symbols:   3906
-  CStrings:  803
+  Functions: 6269
+  Symbols:   3912
+  CStrings:  804
Symbols:
+ -[SCMLImageSanitization hasUnsafeNonRegionalSignal]
+ -[SCMLImageSanitization setHasUnsafeNonRegionalSignal:]
+ -[SCMLTextSanitization hasUnsafeNonRegionalSignal]
+ -[SCMLTextSanitization setHasUnsafeNonRegionalSignal:]
+ _OBJC_IVAR_$_SCMLImageSanitization._hasUnsafeNonRegionalSignal
+ _OBJC_IVAR_$_SCMLTextSanitization._hasUnsafeNonRegionalSignal
CStrings:
+ "Make combined text sanitizer backend failed"
```
