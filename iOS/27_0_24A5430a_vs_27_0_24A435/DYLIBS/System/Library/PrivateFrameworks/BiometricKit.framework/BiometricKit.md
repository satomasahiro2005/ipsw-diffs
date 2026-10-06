## BiometricKit

> `/System/Library/PrivateFrameworks/BiometricKit.framework/BiometricKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x51f8` | `0x5258` | **`+0x60`** |
| `__TEXT.__text` | `0x3c580` | `0x3c59c` | **`+0x1c`** |
| `__TEXT.__objc_methlist` | `0x2cdc` | `0x2cf4` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x1758` | `0x1768` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x2e4` | `0x2ec` | **`+0x8`** |
| `__TEXT.__const` | `0x218` | `0x220` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-  Functions: 1546
-  Symbols:   2083
+  Functions: 1548
+  Symbols:   2086
Symbols:
+ -[BKFaceDetectStateInfo excessiveLight]
+ -[BKFaceDetectStateInfo inadequateLight]
+ GCC_except_table150
+ _OBJC_IVAR_$_BKFaceDetectStateInfo._excessiveLight
+ _OBJC_IVAR_$_BKFaceDetectStateInfo._inadequateLight
- GCC_except_table109
- GCC_except_table155
CStrings:
+ "AssertMacros: %s (value = 0x%lx), version: BiometricKit-577~3088, %s file: %s, line: %d\n\n"
- "AssertMacros: %s (value = 0x%lx), version: BiometricKit-577~3107, %s file: %s, line: %d\n\n"
```
