## SiriVideoFlowTools

> `/System/Library/FlowTools/Tools/SiriVideoFlowTools.flowtool/SiriVideoFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a2b4` | `0x1fb40` | **`+0x588c`** |
| `__TEXT.__eh_frame` | `0x9a0` | `0xce0` | **`+0x340`** |
| `__TEXT.__auth_stubs` | `0xf00` | `0x11f0` | **`+0x2f0`** |
| `__DATA_CONST.__const` | `0xf11` | `0x1141` | **`+0x230`** |
| `__TEXT.__oslogstring` | `0x5f0` | `0x770` | **`+0x180`** |
| `__DATA_CONST.__auth_got` | `0x788` | `0x900` | **`+0x178`** |
| `__TEXT.__unwind_info` | `0x778` | `0x880` | **`+0x108`** |
| `__TEXT.__swift5_typeref` | `0x7af` | `0x89f` | **`+0xf0`** |
| `__TEXT.__swift5_capture` | `0x64` | `0x144` | **`+0xe0`** |
| `__TEXT.__const` | `0x2198` | `0x2260` | **`+0xc8`** |
| `__DATA.__data` | `0x838` | `0x8c0` | **`+0x88`** |
| `__TEXT.__swift5_reflstr` | `0x72e` | `0x7ae` | **`+0x80`** |
| `__DATA.__objc_const` | `0x4d0` | `0x530` | **`+0x60`** |
| `__DATA_CONST.__auth_ptr` | `0xad0` | `0xb30` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x2b8` | `0x310` | **`+0x58`** |
| `__TEXT.__cstring` | `0x15d5` | `0x1625` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x5ff` | `0x64f` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x804` | `0x834` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0x5c` | `0x8c` | **`+0x30`** |
| `__TEXT.__swift_as_ret` | `0x44` | `0x58` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x34` | `0x3c` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-3600.28.7.0.0
+3605.20.2.0.0

-  Functions: 701
-  Symbols:   157
-  CStrings:  191
+  Functions: 869
+  Symbols:   171
+  CStrings:  200
Symbols:
+ __swiftEmptyDictionarySingleton
+ _swift_release_x12
+ _swift_release_x22
+ _swift_release_x25
+ _swift_release_x26
+ _swift_release_x27
+ _swift_release_x28
+ _swift_retain_x22
+ _swift_retain_x23
+ _swift_retain_x24
+ _swift_retain_x25
+ _swift_retain_x26
+ _swift_retain_x27
+ _swift_retain_x28
CStrings:
+ "PlayVideoContentTool: Live Service CDTVC via SiriX — device=%s, service=%s"
+ "PlayVideoContentTool: Sports Event CDTVC via SiriX — device=%s, matchupId=%s"
+ "PlayVideoContentTool: failed to set up AirPlay route to %s for freeform CDTVC: %s"
+ "PlayVideoContentTool: unable to find content parameter type in %s"
+ "PlayVideoContentToolError: Failed to set up AirPlay route to the target device"
+ "allowBackgroundPlayback"
+ "deviceLockProvider"
+ "getAppIntentTool found %ld local candidate tools for %s"
+ "getAppIntentTool found %ld remote client candidate tools for %s"
+ "moveToGroupDevices"
- "PlayVideoContentTool: content type is not supported for CDTVC (yet)"
```
