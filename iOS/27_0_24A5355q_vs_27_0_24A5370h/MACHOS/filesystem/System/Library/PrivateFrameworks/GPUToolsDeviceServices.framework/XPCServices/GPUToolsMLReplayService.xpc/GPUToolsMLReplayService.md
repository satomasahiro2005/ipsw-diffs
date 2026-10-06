## GPUToolsMLReplayService

> `/System/Library/PrivateFrameworks/GPUToolsDeviceServices.framework/XPCServices/GPUToolsMLReplayService.xpc/GPUToolsMLReplayService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4b188` | `0x4ca84` | **`+0x18fc`** |
| `__TEXT.__cstring` | `0x26c6` | `0x27e6` | **`+0x120`** |
| `__DATA.__objc_const` | `0x5960` | `0x59c0` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x4032` | `0x4082` | **`+0x50`** |
| `__DATA_CONST.__cfstring` | `0x2160` | `0x21a0` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x2b20` | `0x2b60` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x1594` | `0x15c4` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x2b6c` | `0x2b94` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x5a8` | `0x5c8` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x2290` | `0x22b0` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x75b` | `0x775` | **`+0x1a`** |
| `__DATA.__objc_selrefs` | `0xfa0` | `0xfb8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xfb0` | `0xf98` | **`-0x18`** |
| `__DATA.__data` | `0x13f0` | `0x1400` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1150` | `0x1160` | **`+0x10`** |
| `__TEXT.__const` | `0xa18` | `0xa08` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x304` | `0x30c` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x338` | `0x340` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2027.0.28.0.0
+2027.0.31.0.0

-  Functions: 1411
+  Functions: 1412

-  CStrings:  1380
+  CStrings:  1393
CStrings:
+ "Could not create function for entry point"
+ "Could not create function for entry point "
+ "Failed to create tensor"
+ "Failed to load capture model"
+ "Failed to read input tensor"
+ "GTMLReplayCompileIdentifiers(odixId: %llu, delegateId: %llu)"
+ "Missing descriptor for tensor"
+ "Numpy tensor doesn't match expected shape."
+ "T@\"NSObject<OS_xpc_object>\",&"
+ "T@\"NSObject<OS_xpc_object>\",&,V_error"
+ "TQ,V_delegateId"
+ "Tq,V_index"
+ "Tq,V_intermediateType"
+ "_delegateId"
+ "_index"
+ "_intermediateType"
+ "delegateId"
+ "intermediateType"
+ "setDelegateId:"
+ "setIndex:"
+ "setIntermediateType:"
- "GTMLReplayCompileIdentifiers(odixId: %llu, debugInfoIds: %@)"
- "T@\"NSArray\",&,V_debugInfoIds"
- "T@\"NSObject<OS_xpc_object>\",&,N"
- "T@\"NSObject<OS_xpc_object>\",&,N,V_error"
- "_debugInfoIds"
- "debugInfoIds"
- "initWithUnsignedLongLong:"
- "setDebugInfoIds:"
```
