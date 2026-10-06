## AVCPlugin

> `/System/Library/ExtensionKit/Extensions/AVCPlugin.appex/AVCPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15a64` | `0x15638` | **`-0x42c`** |
| `__TEXT.__oslogstring` | `0x196` | `0x146` | **`-0x50`** |
| `__TEXT.__auth_stubs` | `0x11a0` | `0x1170` | **`-0x30`** |
| `__TEXT.__const` | `0xe48` | `0xe28` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0x8d8` | `0x8c0` | **`-0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x308` | `0x310` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x240` | `0x248` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0xed8` | `0xee0` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x36a` | `0x370` | **`+0x6`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-38.0.0.0.0
+42.0.0.0.0

-  - /System/Library/PrivateFrameworks/PriMLDataPolicy.framework/PriMLDataPolicy

-  Functions: 393
+  Functions: 394
CStrings:
+ "preference"
- "Failed to decode AVCCustomTaskParameters from PluginPreference: %@"
```
