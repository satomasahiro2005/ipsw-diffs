## identityservicesd

> `/System/Library/PrivateFrameworks/IDS.framework/identityservicesd.app/identityservicesd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaefc74` | `0xaeff64` | **`+0x2f0`** |
| `__TEXT.__objc_methname` | `0x7de75` | `0x7deb5` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x8c1e3` | `0x8c223` | **`+0x40`** |
| `__TEXT.__cstring` | `0x5b8c9` | `0x5b8f9` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0x37b40` | `0x37b60` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x4b260` | `0x4b280` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x24d2c` | `0x24d3c` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x17418` | `0x17420` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x46f8` | `0x4700` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x2cd74` | `0x2cd7c` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2003.200.61.0.0
+2003.200.71.2.3

-  Functions: 32979
-  Symbols:   2990
-  CStrings:  33618
+  Functions: 32980
+  Symbols:   2991
+  CStrings:  33621
Symbols:
+ _IDSGroupSessionClientParametersKey
CStrings:
+ "00:41:41"
+ "HomeAccessory"
+ "Oct  8 2026"
+ "_isSupportPhoneCallRelayOptimizationFlagSet"
+ "endpointContextForService:trustCircles:parameters:completion:"
+ "hello (controlChannelVersion: [%@], productName: [%@], productVersion: [%@], productBuildVersion: [%@], model: [%@], protocol: %@ minCompatibilityVersion: %@ maxCompatibilityVersion: %@ deviceUniqueID: %@ instanceID: %@, supportIPsecLink:%@, isTinker: %@, supportPhoneCallRelayOptimization: %@)"
+ "registerEntitledAgent: not requiring %s on this device class"
+ "startDataChannelWithDevice: nw_quic_set_phone_call_relay_optimization: %@ for %@"
- "22:39:06"
- "Sep 27 2026"
- "endpointContextForService:trustCircles:completion:"
- "hello (controlChannelVersion: [%@], productName: [%@], productVersion: [%@], productBuildVersion: [%@], model: [%@], protocol: %@ minCompatibilityVersion: %@ maxCompatibilityVersion: %@ deviceUniqueID: %@ instanceID: %@, supportIPsecLink:%@, isTinker: %@)"
- "peelDatagramConnectionForService:nw_quic_set_phone_call_relay_optimization"
```
