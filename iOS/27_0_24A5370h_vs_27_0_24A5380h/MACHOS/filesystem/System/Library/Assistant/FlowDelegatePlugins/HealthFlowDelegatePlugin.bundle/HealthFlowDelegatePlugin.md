## HealthFlowDelegatePlugin

> `/System/Library/Assistant/FlowDelegatePlugins/HealthFlowDelegatePlugin.bundle/HealthFlowDelegatePlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6cb74` | `0x6cb90` | **`+0x1c`** |
| `__TEXT.__const` | `0x6ec8` | `0x6ed8` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x1146` | `0x1156` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.12.4.1.1
+3600.12.12.0.0

-  Functions: 2947
+  Functions: 2949
CStrings:
+ "Found instructor,  assuming search required: %{sensitive}s with modality: %@"
+ "[StartWorkout HandleIntentStrategy] Candidate %s apps: %{sensitive}s"
- "Found instructor,  assuming search required: %s with modality: %@"
- "[StartWorkout HandleIntentStrategy] Candidate %s apps: %s"
```
