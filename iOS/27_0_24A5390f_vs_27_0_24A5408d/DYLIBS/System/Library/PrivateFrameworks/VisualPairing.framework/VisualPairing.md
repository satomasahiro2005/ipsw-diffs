## VisualPairing

> `/System/Library/PrivateFrameworks/VisualPairing.framework/VisualPairing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1dd70` | `0x1df10` | **`+0x1a0`** |
| `__TEXT.__gcc_except_tab` | `0x474` | `0x4cc` | **`+0x58`** |
| `__AUTH_CONST.__objc_const` | `0xf30` | `0xf50` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x4b8` | `0x4d8` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x75c` | `0x774` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x750` | `0x760` | **`+0x10`** |
| `__DATA.__data` | `0x360` | `0x368` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x100` | `0x104` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-203.100.1.0.0
+205.100.1.0.0

-  Functions: 337
-  Symbols:   680
+  Functions: 339
+  Symbols:   685
Symbols:
+ -[VPScannerView _applyPreviewRotationFromCoordinator]
+ -[VPScannerView observeValueForKeyPath:ofObject:change:context:]
+ GCC_except_table18
+ GCC_except_table19
+ _NSStringFromSelector
+ _OBJC_CLASS_$_AVCaptureDeviceRotationCoordinator
+ _objc_retain_x23
- _UIApp
- _gLogCategory_SV
Functions:
~ -[VPScannerView stop] : 428 -> 524
~ -[VPScannerView _setupCapture] : 1584 -> 1524
+ -[VPScannerView observeValueForKeyPath:ofObject:change:context:]
+ -[VPScannerView _handleCaptureSessionStopped:]
~ -[VPScannerView .cxx_destruct] : 212 -> 228
```
