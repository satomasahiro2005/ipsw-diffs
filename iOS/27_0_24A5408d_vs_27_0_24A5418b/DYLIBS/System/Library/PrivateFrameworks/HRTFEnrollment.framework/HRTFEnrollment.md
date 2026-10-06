## HRTFEnrollment

> `/System/Library/PrivateFrameworks/HRTFEnrollment.framework/HRTFEnrollment`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x93c0` | `0x969c` | **`+0x2dc`** |
| `__TEXT.__oslogstring` | `0x4e7` | `0x52d` | **`+0x46`** |
| `__AUTH_CONST.__const` | `0x180` | `0x1c0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x98a` | `0x9a7` | **`+0x1d`** |
| `__DATA.__bss` | `0x48` | `0x60` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x338` | `0x350` | **`+0x18`** |

### Other Changes

```diff

-40.41.1.1.4
+40.41.1.1.7

-  Functions: 182
-  Symbols:   597
-  CStrings:  160
+  Functions: 189
+  Symbols:   604
+  CStrings:  164
Symbols:
+ _HRTFCreateDummyDepthPixelBuffer
+ _HRTFDepthFormatNotSupported
+ _HRTFDepthFormatNotSupported.onceToken
+ ___HRTFDepthFormatNotSupported_block_invoke
+ ___HRTFLogObjectForCategory_HRTFDeviceCapabilities_block_invoke
+ _logObjHRTFDeviceCapabilities
+ _onceTokenHRTFDeviceCapabilities
CStrings:
+ "False"
+ "HRTFDeviceCapabilities"
+ "depthFormatNotSupported -> %s"
+ "failed to create dummy depth buffer: %d"
```
