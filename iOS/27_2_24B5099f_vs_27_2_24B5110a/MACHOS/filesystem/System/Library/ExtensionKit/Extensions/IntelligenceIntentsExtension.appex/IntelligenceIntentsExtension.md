## IntelligenceIntentsExtension

> `/System/Library/ExtensionKit/Extensions/IntelligenceIntentsExtension.appex/IntelligenceIntentsExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21214` | `0x21280` | **`+0x6c`** |
| `__TEXT.__objc_methname` | `0x48b` | `0x4bb` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x12d8` | `0x12b0` | **`-0x28`** |
| `__TEXT.__objc_stubs` | `0x540` | `0x560` | **`+0x20`** |
| `__DATA.__data` | `0xd48` | `0xd50` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x160` | `0x168` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1626.200.84.0.0
+1626.200.91.2.3

-  Functions: 1116
+  Functions: 1117

-  CStrings:  249
+  CStrings:  250
CStrings:
+ "isJunkFilteringAvailable"
+ "isSilenceJunkCallingUserPreferenceEnabled"
+ "setSilenceJunkCallingUserPreferenceEnabled:"
- "isSilenceJunkCallingEnabled"
- "setSilenceJunkCallingEnabled:"
```
