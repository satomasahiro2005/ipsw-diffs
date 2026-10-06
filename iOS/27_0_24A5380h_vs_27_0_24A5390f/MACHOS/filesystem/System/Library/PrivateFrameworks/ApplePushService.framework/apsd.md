## apsd

> `/System/Library/PrivateFrameworks/ApplePushService.framework/apsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1177f0` | `0x117900` | **`+0x110`** |
| `__TEXT.__objc_methtype` | `0x5559` | `0x5519` | **`-0x40`** |
| `__TEXT.__oslogstring` | `0x14125` | `0x14165` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x1b8d5` | `0x1b8a5` | **`-0x30`** |
| `__TEXT.__objc_methlist` | `0xb7f0` | `0xb7c8` | **`-0x28`** |
| `__TEXT.__objc_stubs` | `0x10ba0` | `0x10b80` | **`-0x20`** |
| `__DATA.__objc_const` | `0x1c540` | `0x1c550` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x2680` | `0x2670` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x5668` | `0x5660` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0xbb0` | `0xbb4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1163.100.1.0.0
+1165.100.1.0.0

-  Functions: 6772
+  Functions: 6770
CStrings:
+ "%@ Closed without starting connection, refunding offload info"
+ "%@: Burning offload info for connection attempt"
+ "_connectionStarted"
+ "insertObject:atIndex:"
+ "tcpStream:receivedOffloadInfo:onInterface:"
+ "v40@0:8@\"<APSTCPStream>\"16@\"APSConnectionOffloadInfo\"24q32"
- "%@: Burning offload info to start connection"
- "courierConnection:willStartConnectionWithOffloadInfo:"
- "tcpStream:receivedOffloadInfo:"
- "tcpStream:willStartConnectionWithOffloadInfo:"
- "v32@0:8@\"<APSTCPStream>\"16@\"APSConnectionOffloadInfo\"24"
- "v32@0:8@\"APSCourierConnection\"16@\"APSConnectionOffloadInfo\"24"
```
