## ClipServices

> `/System/Library/PrivateFrameworks/ClipServices.framework/ClipServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x382a0` | `0x3839c` | **`+0xfc`** |
| `__TEXT.__cstring` | `0x3f09` | `0x3f4a` | **`+0x41`** |
| `__AUTH_CONST.__cfstring` | `0x3460` | `0x34a0` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x19d8` | `0x19e8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x10c0` | `0x10d0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x4c8` | `0x4d0` | **`+0x8`** |

### Other Changes

```diff

-1038.7.0.0.0
+1038.8.1.0.0

-  Functions: 1485
-  Symbols:   2486
-  CStrings:  830
+  Functions: 1487
+  Symbols:   2490
+  CStrings:  832
Symbols:
+ _CPSSimulateAppClipNeedsUpdateForTesting
+ _CPSSimulateAppClipNeedsUpdateForTestingKey
+ _CPSSimulateExtensionCourierAppClipForTesting
+ _CPSSimulateExtensionCourierAppClipForTestingKey
CStrings:
+ "CPSSimulateAppClipNeedsUpdate"
+ "CPSSimulateExtensionCourierAppClip"
```
