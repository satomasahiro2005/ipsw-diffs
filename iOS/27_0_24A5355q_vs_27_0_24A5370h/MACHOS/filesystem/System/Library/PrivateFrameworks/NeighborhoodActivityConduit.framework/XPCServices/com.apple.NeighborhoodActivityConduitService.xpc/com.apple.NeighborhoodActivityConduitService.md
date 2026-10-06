## com.apple.NeighborhoodActivityConduitService

> `/System/Library/PrivateFrameworks/NeighborhoodActivityConduit.framework/XPCServices/com.apple.NeighborhoodActivityConduitService.xpc/com.apple.NeighborhoodActivityConduitService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10d490` | `0x10dd70` | **`+0x8e0`** |
| `__TEXT.__oslogstring` | `0x577c` | `0x582c` | **`+0xb0`** |
| `__TEXT.__eh_frame` | `0xb558` | `0xb4c8` | **`-0x90`** |
| `__DATA.__data` | `0x30b0` | `0x3100` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x57e8` | `0x5838` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x64d7` | `0x651b` | **`+0x44`** |
| `__DATA.__objc_const` | `0x3dc8` | `0x3df8` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x38d0` | `0x38a0` | **`-0x30`** |
| `__TEXT.__objc_stubs` | `0x2aa0` | `0x2ac0` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x15a0` | `0x15b8` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x1564` | `0x157c` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x2468` | `0x2478` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0xde4` | `0xdec` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1608.100.12.2.6
+1612.100.3.2.1

-  Functions: 3399
+  Functions: 3403

-  CStrings:  1474
+  CStrings:  1480
CStrings:
+ "Handle calls changed with %ld calls."
+ "[ContinuityCalls][%s] Filtering %ld current calls"
+ "[ContinuityCalls][%s] Returning %ld current continuity calls"
+ "callContextCardAllLanguagesEnabled"
+ "requeryRoutes"
+ "smartVoicemailActionsAllLanguagesEnabled"
```
