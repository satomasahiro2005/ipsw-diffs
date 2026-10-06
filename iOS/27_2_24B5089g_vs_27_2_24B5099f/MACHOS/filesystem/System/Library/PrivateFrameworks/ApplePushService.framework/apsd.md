## apsd

> `/System/Library/PrivateFrameworks/ApplePushService.framework/apsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1203cc` | `0x1207f0` | **`+0x424`** |
| `__TEXT.__objc_methname` | `0x1bdc5` | `0x1bef5` | **`+0x130`** |
| `__TEXT.__oslogstring` | `0x14525` | `0x145e5` | **`+0xc0`** |
| `__TEXT.__objc_stubs` | `0x10ee0` | `0x10f80` | **`+0xa0`** |
| `__DATA.__objc_const` | `0x1d1b0` | `0x1d210` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0xb990` | `0xb9e0` | **`+0x50`** |
| `__DATA_CONST.__cfstring` | `0x85c0` | `0x8600` | **`+0x40`** |
| `__TEXT.__cstring` | `0xfe43` | `0xfe83` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x5730` | `0x5760` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xa380` | `0xa3a0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x44c0` | `0x44e0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x2680` | `0x2698` | **`+0x18`** |
| `__DATA.__bss` | `0x15c0` | `0x15d0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xbc8` | `0xbd0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1168.200.41.0.0
+1168.200.51.0.0

-  Functions: 7003
+  Functions: 7012

-  CStrings:  8696
+  CStrings:  8712
CStrings:
+ "%@ not resending deferred daemonAlive, no longer nearby"
+ "%@ previous daemonAlive failed with retry later, resending in %f seconds"
+ "%@ previous daemonAlive failed with retry later, retry already scheduled"
+ "IDSFoundation"
+ "IDSSendErrorDomain"
+ "TB,N,V_mainQueue_daemonAliveRetryScheduled"
+ "Td,N,V_retryLaterDelay"
+ "_isRetryLaterError:"
+ "_mainQueue_daemonAliveRetryScheduled"
+ "_resendDaemonAliveMessageAfterFailureWithError:"
+ "_retryLaterDelay"
+ "com.apple.ids.idssenderrordomain"
+ "mainQueue_daemonAliveRetryScheduled"
+ "retryLaterDelay"
+ "setMainQueue_daemonAliveRetryScheduled:"
+ "setRetryLaterDelay:"
```
