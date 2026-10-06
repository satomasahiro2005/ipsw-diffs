## BiometricKitUI

> `/System/Library/PrivateFrameworks/BiometricKitUI.framework/BiometricKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x70534` | `0x70b1c` | **`+0x5e8`** |
| `__TEXT.__oslogstring` | `0x6853` | `0x6963` | **`+0x110`** |
| `__AUTH_CONST.__cfstring` | `0x33a0` | `0x3400` | **`+0x60`** |
| `__TEXT.__cstring` | `0x2fd6` | `0x3026` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x48d8` | `0x4918` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x72c0` | `0x72e0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1ac0` | `0x1ac8` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 2868
-  Symbols:   4579
-  CStrings:  1068
+  Functions: 2875
+  Symbols:   4582
+  CStrings:  1078
Symbols:
+ -[BKUIPearlVideoCaptureSession configureFaceIDCoexistenceForCamera:]
+ -[BKUIPearlVideoCaptureSession enableFaceIDCoexistenceForCamera:]
+ -[BKUIPearlVideoCaptureSession findCoexistenceSupportedFormatForCamera:]
CStrings:
+ "Coexistence: Cannot enable coexistence for nil camera"
+ "Coexistence: Cannot find format for nil camera"
+ "Coexistence: Enabling for: %@"
+ "Coexistence: Failed to find a supported format"
+ "Coexistence: Failed to lock camera for configuration: %@"
+ "Coexistence: Unsupported"
+ "Pearl-rgbCamera"
+ "Too little light"
+ "Too much light from backlit Sun"
+ "jindo_coexistence"
```
