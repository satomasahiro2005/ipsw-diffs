## WellnessFlowPlugin

> `/System/Library/Assistant/FlowDelegatePlugins/WellnessFlowPlugin.bundle/WellnessFlowPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x166d04` | `0x166ee0` | **`+0x1dc`** |
| `__TEXT.__oslogstring` | `0x6ea3` | `0x6f03` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x7b18` | `0x7b48` | **`+0x30`** |
| `__TEXT.__cstring` | `0x6e55` | `0x6e75` | **`+0x20`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.12.14.0.0
+3600.12.16.0.0

-  Functions: 7897
+  Functions: 7901

-  CStrings:  1608
+  CStrings:  1610
CStrings:
+ "Cannot determine if isLoggingSupported for nil identifier. Assuming it is unsupported."
+ "Cannot determine if isManualLoggingSupported for nil identifier. Assuming it is supported."
+ "isLoggingSupported"
- "Cannot determine if isLoggingSupported for nil identifier. Assuming it is supported."
```
