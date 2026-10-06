## AudioFlowDelegatePlugin

> `/System/Library/Assistant/FlowDelegatePlugins/AudioFlowDelegatePlugin.bundle/AudioFlowDelegatePlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2cac64` | `0x2cc594` | **`+0x1930`** |
| `__DATA.__data` | `0xc330` | `0xc340` | **`+0x10`** |
| `__TEXT.__const` | `0xc08a` | `0xc09a` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x2467c` | `0x2466c` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x3830` | `0x3840` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x471e` | `0x472a` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.33.2.0.0
+3600.33.6.0.0
CStrings:
+ "PlayMediaAppResolver#postResolve %{public}s skipping app selection signals record, disambiguation reason: %{public}s"
- "PlayMediaAppResolver#postResolve %{public}s skipping app selection signals record as the app was not explicitly chosen by the user"
```
