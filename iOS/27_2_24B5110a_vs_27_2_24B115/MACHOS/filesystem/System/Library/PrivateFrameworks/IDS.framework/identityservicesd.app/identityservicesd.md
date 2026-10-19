## identityservicesd

> `/System/Library/PrivateFrameworks/IDS.framework/identityservicesd.app/identityservicesd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaeff64` | `0xaf09cc` | **`+0xa68`** |
| `__TEXT.__oslogstring` | `0x8c223` | `0x8c3f3` | **`+0x1d0`** |
| `__TEXT.__cstring` | `0x5b8f9` | `0x5b9d9` | **`+0xe0`** |
| `__DATA_CONST.__cfstring` | `0x37b60` | `0x37bc0` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x31878` | `0x318a8` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x7deb5` | `0x7dee5` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x24d3c` | `0x24d60` | **`+0x24`** |
| `__DATA.__objc_const` | `0x538d0` | `0x538f0` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x4b280` | `0x4b2a0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x17a58` | `0x17a70` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x17420` | `0x17428` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x2cd7c` | `0x2cd84` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x3598` | `0x359c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
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

### Other Changes

```diff

-2003.200.71.2.3
+2003.200.71.2.4

-  Functions: 32980
+  Functions: 32988

-  CStrings:  33621
+  CStrings:  33630
CStrings:
+ "20:39:11"
+ "Can not ingest remote participant leave notification as cleanUpBlock not set!"
+ "IDSGroupSessionMessageParticipantUpdateTypeParticipantLeft"
+ "Oct 11 2026"
+ "_cleanUpBlock"
+ "_notifyLeaveWithOptions:"
+ "_notifyLeaveWithOptions: cannot notify leave for session: %@ destinationsArray: %@ localURI: %@ account: %@"
+ "_notifyLeaveWithOptions: sending remote participant left notification for session: %@ destinationsArray: %@ localURI: %@ account: %@"
+ "browse_handler: invalid message type: %lu from destination: %@"
+ "browse_handler: received participant left, message: %@ from destination: %@"
+ "browse_handler: remote left notification received with nil sessionID."
- "00:41:41"
- "Oct  8 2026"
```
