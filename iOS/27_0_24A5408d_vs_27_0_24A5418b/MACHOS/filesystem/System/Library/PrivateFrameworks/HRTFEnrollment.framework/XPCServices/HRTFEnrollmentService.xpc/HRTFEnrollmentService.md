## HRTFEnrollmentService

> `/System/Library/PrivateFrameworks/HRTFEnrollment.framework/XPCServices/HRTFEnrollmentService.xpc/HRTFEnrollmentService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7618` | `0x78f4` | **`+0x2dc`** |
| `__TEXT.__oslogstring` | `0x557` | `0x59d` | **`+0x46`** |
| `__DATA_CONST.__const` | `0x2e8` | `0x328` | **`+0x40`** |
| `__TEXT.__cstring` | `0x561` | `0x57e` | **`+0x1d`** |
| `__DATA.__bss` | `0x30` | `0x48` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1e0` | `0x1f8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xe0` | `0xf0` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x570` | `0x580` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x2c8` | `0x2d0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-40.41.1.1.4
+40.41.1.1.7

-  Functions: 134
-  Symbols:   145
-  CStrings:  501
+  Functions: 141
+  Symbols:   150
+  CStrings:  505
Symbols:
+ _CVPixelBufferCreate
+ _HRTFCreateDummyDepthPixelBuffer
+ _HRTFDepthFormatNotSupported
+ ___NSDictionary0__struct
+ _kCVPixelBufferIOSurfacePropertiesKey
CStrings:
+ "False"
+ "HRTFDeviceCapabilities"
+ "depthFormatNotSupported -> %s"
+ "failed to create dummy depth buffer: %d"
```
