## WellnessFlowPlugin

> `/System/Library/Assistant/FlowDelegatePlugins/WellnessFlowPlugin.bundle/WellnessFlowPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1626fc` | `0x16370c` | **`+0x1010`** |
| `__DATA_CONST.__const` | `0x78d0` | `0x7ab0` | **`+0x1e0`** |
| `__TEXT.__swift5_capture` | `0x1090` | `0x1150` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0x55b0` | `0x5618` | **`+0x68`** |
| `__TEXT.__oslogstring` | `0x6d73` | `0x6da3` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0xf0e0` | `0xf0f8` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x3390` | `0x33a0` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x3077` | `0x3083` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x19d0` | `0x19d8` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0xd64` | `0xd68` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0xae0` | `0xae4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-3600.8.4.0.0
+3600.12.4.1.1

-  Functions: 7817
-  Symbols:   399
-  CStrings:  1603
+  Functions: 7848
+  Symbols:   400
+  CStrings:  1604
Symbols:
+ _bzero
CStrings:
+ "%s shouldAskForSafetyConfirmation: %{bool}d hasAskedForSafetyConfirmation: %{bool}d"
+ "As needed meds, asking for confirmation"
- "SpecificMedLoggingFlow: Non-scheduled medication detected, requesting safety confirmation"
```
