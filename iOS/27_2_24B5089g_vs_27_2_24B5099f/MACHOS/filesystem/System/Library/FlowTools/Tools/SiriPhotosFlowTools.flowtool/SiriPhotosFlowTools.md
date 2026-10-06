## SiriPhotosFlowTools

> `/System/Library/FlowTools/Tools/SiriPhotosFlowTools.flowtool/SiriPhotosFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13c24` | `0x162e8` | **`+0x26c4`** |
| `__TEXT.__auth_stubs` | `0xb90` | `0xcf0` | **`+0x160`** |
| `__TEXT.__eh_frame` | `0x9f8` | `0xae0` | **`+0xe8`** |
| `__TEXT.__oslogstring` | `0x741` | `0x801` | **`+0xc0`** |
| `__DATA_CONST.__auth_got` | `0x5d0` | `0x680` | **`+0xb0`** |
| `__TEXT.__const` | `0xed8` | `0xf88` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x209` | `0x2a9` | **`+0xa0`** |
| `__DATA_CONST.__got` | `0x1c8` | `0x218` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x578` | `0x5a8` | **`+0x30`** |
| `__DATA.__data` | `0x498` | `0x4b8` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x590` | `0x5b0` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x400` | `0x41c` | **`+0x1c`** |
| `__TEXT.__swift5_builtin` | `—` | `0x14` | **`+0x14`** |
| `__TEXT.__swift_as_cont` | `0x70` | `0x7c` | **`+0xc`** |
| `__TEXT.__swift5_mpenum` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x4c` | `0x54` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x38` | `0x3c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-3605.2.1.0.0
+3605.4.1.0.0

-  Functions: 581
-  Symbols:   107
-  CStrings:  77
+  Functions: 605
+  Symbols:   108
+  CStrings:  84
Symbols:
+ _swift_errorRelease
CStrings:
+ "App-launch AppIntent not found on the Watch [bundleID=%s]"
+ "Editing photos isn't supported on this device"
+ "LaunchApplicationIntent"
+ "Successfully launched Camera Remote on the Watch"
+ "Taking photos isn't supported on this device"
+ "Watch request - launching Camera Remote instead of capturing"
+ "com.apple.Carousel"
+ "com.apple.NanoCamera"
- "No app intent found"
```
