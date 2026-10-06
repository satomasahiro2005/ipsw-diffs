## IDSBlastDoorService

> `/System/Library/PrivateFrameworks/IDSBlastDoorSupport.framework/XPCServices/IDSBlastDoorService.xpc/IDSBlastDoorService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc1fcc` | `0xc4238` | **`+0x226c`** |
| `__DATA.__bss` | `0x1f880` | `0x20200` | **`+0x980`** |
| `__TEXT.__const` | `0x14030` | `0x148c0` | **`+0x890`** |
| `__DATA_CONST.__const` | `0xc4e0` | `0xc738` | **`+0x258`** |
| `__TEXT.__constg_swiftt` | `0x2304` | `0x2558` | **`+0x254`** |
| `__TEXT.__eh_frame` | `0x59c8` | `0x5b90` | **`+0x1c8`** |
| `__TEXT.__swift5_assocty` | `0xab0` | `0xc78` | **`+0x1c8`** |
| `__TEXT.__swift5_reflstr` | `0x3642` | `0x37d2` | **`+0x190`** |
| `__TEXT.__swift5_typeref` | `0x2bd7` | `0x2d4f` | **`+0x178`** |
| `__DATA_CONST.__got` | `0xa08` | `0xb30` | **`+0x128`** |
| `__TEXT.__swift5_fieldmd` | `0x5d00` | `0x5e14` | **`+0x114`** |
| `__TEXT.__cstring` | `0x28ff` | `0x29ff` | **`+0x100`** |
| `__DATA.__data` | `0x4a80` | `0x4b10` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x2e98` | `0x2e30` | **`-0x68`** |
| `__TEXT.__auth_stubs` | `0x2b80` | `0x2be0` | **`+0x60`** |
| `__TEXT.__swift5_types` | `0x464` | `0x4b8` | **`+0x54`** |
| `__TEXT.__oslogstring` | `0x323` | `0x36f` | **`+0x4c`** |
| `__TEXT.__swift5_proto` | `0xfc4` | `0x1010` | **`+0x4c`** |
| `__DATA_CONST.__auth_ptr` | `0x9b0` | `0x9e8` | **`+0x38`** |
| `__DATA_CONST.__auth_got` | `0x15c8` | `0x15f8` | **`+0x30`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-322.100.2.2.1
+324.100.2.0.0

-  Functions: 3843
-  Symbols:   137
-  CStrings:  624
+  Functions: 3907
+  Symbols:   135
+  CStrings:  627
Symbols:
- _objc_release_x28
- _swift_release_x26
CStrings:
+ "Invalid StatusKit invitation payload: failed to decode base64."
+ "InvalidBase64Decode"
+ "SharedETATrip messages are no longer supported through IDS XAF. Process messages through MapsBlastDoorSupport instead."
+ "StatusKitInvitationPayload"
+ "com.apple.BlastDoor.StatusKitInvitationPayload"
+ "com.apple.focus.status"
+ "com.apple.offgrid.status"
+ "invitationPayload"
- "chunkDataKey"
- "chunkGroupIDKey"
- "chunkIndexKey"
- "chunkMessageIDKey"
- "chunkNumberKey"
```
