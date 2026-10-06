## HRTFEnrollmentService

> `/System/Library/PrivateFrameworks/HRTFEnrollment.framework/XPCServices/HRTFEnrollmentService.xpc/HRTFEnrollmentService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x78f4` | `0x7a40` | **`+0x14c`** |
| `__TEXT.__objc_stubs` | `0x12c0` | `0x1300` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x1768` | `0x179c` | **`+0x34`** |
| `__TEXT.__cstring` | `0x57e` | `0x5af` | **`+0x31`** |
| `__TEXT.__const` | `0x98` | `0xb8` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x214` | `0x22c` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x680` | `0x690` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x580` | `0x590` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x59d` | `0x58e` | **`-0xf`** |
| `__DATA.__bss` | `0x48` | `0x50` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x2d0` | `0x2d8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-40.41.1.1.7
+40.41.1.1.10

+  - /usr/lib/libMobileGestalt.dylib

-  Symbols:   150
-  CStrings:  505
+  Symbols:   151
+  CStrings:  510
Symbols:
+ _MGIsDeviceOfType
CStrings:
+ "%s returned with %@"
+ "True"
+ "getAssetForEnrollmentMode"
+ "getAssetForEnrollmentMode:error:"
+ "getAssetWithError"
+ "setEnrollmentMode:"
- "getAssetWithError returned with %@"
```
