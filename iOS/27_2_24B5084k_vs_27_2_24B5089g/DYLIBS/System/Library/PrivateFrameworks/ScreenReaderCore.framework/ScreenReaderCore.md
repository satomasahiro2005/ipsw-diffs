## ScreenReaderCore

> `/System/Library/PrivateFrameworks/ScreenReaderCore.framework/ScreenReaderCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24fa0` | `0x252c4` | **`+0x324`** |
| `__DATA.__data` | `0x2e8` | `—` | **`-0x2e8`** |
| `__DATA_DIRTY.__data` | `—` | `0x2e8` | **`+0x2e8`** |
| `__AUTH_CONST.__objc_const` | `0x4300` | `0x4340` | **`+0x40`** |
| `__TEXT.__const` | `0x7b0` | `0x798` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0x2afc` | `0x2b0c` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x2cc` | `0x2d4` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1a18` | `0x1a20` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xa40` | `0xa48` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-285.0.0.0.0
+285.0.1.0.0

-  Functions: 942
-  Symbols:   2030
-  CStrings:  646
+  Functions: 944
+  Symbols:   2034
+  CStrings:  647
Symbols:
+ -[SCRCGestureFactory _classifyFourFingerScaleForEvent:pinchDistance:]
+ _OBJC_IVAR_$_SCRCGestureFactory._startFingerCentroid
+ _OBJC_IVAR_$_SCRCGestureFactory._startFingerSpread
+ __getSpreadAndCentroidForEvent
CStrings:
+ "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0F"
+ "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xa1\xf0\xf0\xc3"
- "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0q\xf0\xf0\xc3"
```
