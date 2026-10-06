## GPUToolsMLReplayService

> `/System/Library/PrivateFrameworks/GPUToolsDeviceServices.framework/XPCServices/GPUToolsMLReplayService.xpc/GPUToolsMLReplayService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4c9dc` | `0x4cbc4` | **`+0x1e8`** |
| `__TEXT.__objc_methname` | `0x4082` | `0x40c2` | **`+0x40`** |
| `__DATA.__objc_const` | `0x59c0` | `0x59f0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x12a0` | `0x12c8` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x21a0` | `0x21c0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x27e6` | `0x2806` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x2b60` | `0x2b80` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x2b94` | `0x2bac` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0xfb8` | `0xfc8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xf98` | `0xfa8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x30c` | `0x310` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2027.0.37.0.0
+2027.0.44.0.0

-  Functions: 1412
-  Symbols:   517
-  CStrings:  1393
+  Functions: 1416
+  Symbols:   519
+  CStrings:  1397
Symbols:
+ _MessageOriginatorIsUntrusted
+ _hideDeviceUDIDInURLIfUntrusted
CStrings:
+ "<%@: protocolName=%@ protocolMethods=%@ servicePort=%llu platform=%u deviceUDID=%@ version=%llu accessLevel=%llu>"
+ "TQ,N,V_accessLevel"
+ "_accessLevel"
+ "accessLevel"
+ "setAccessLevel:"
- "<%@: protocolName=%@ protocolMethods=%@ servicePort=%llu platform=%u deviceUDID=%@ version=%llu>"
```
