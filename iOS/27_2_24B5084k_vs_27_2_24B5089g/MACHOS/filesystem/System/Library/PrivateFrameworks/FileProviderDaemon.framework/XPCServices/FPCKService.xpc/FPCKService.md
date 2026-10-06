## FPCKService

> `/System/Library/PrivateFrameworks/FileProviderDaemon.framework/XPCServices/FPCKService.xpc/FPCKService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1818` | `0x1904` | **`+0xec`** |
| `__TEXT.__objc_stubs` | `0x380` | `0x3e0` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x1ae` | `0x208` | **`+0x5a`** |
| `__TEXT.__objc_methname` | `0x85a` | `0x88b` | **`+0x31`** |
| `__TEXT.__cstring` | `0xf7` | `0x11b` | **`+0x24`** |
| `__DATA_CONST.__cfstring` | `0x60` | `0x80` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x480` | `0x4a0` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x208` | `0x220` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x250` | `0x260` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x40` | `0x48` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-4838.40.53.502.1
+4838.40.92.502.1

-  Functions: 41
-  Symbols:   95
-  CStrings:  164
+  Functions: 42
+  Symbols:   98
+  CStrings:  169
Symbols:
+ _OBJC_CLASS_$_NSNumber
+ _objc_opt_class
+ _objc_opt_isKindOfClass
CStrings:
+ "[ERROR] FPCKService, rejecting connection from PID %d: missing the %{public}@ entitlement"
+ "boolValue"
+ "com.apple.fileprovider.fpck-service"
+ "processIdentifier"
+ "valueForEntitlement:"
```
