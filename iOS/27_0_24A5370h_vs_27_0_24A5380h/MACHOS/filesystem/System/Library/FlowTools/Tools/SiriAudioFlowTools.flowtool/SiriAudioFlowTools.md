## SiriAudioFlowTools

> `/System/Library/FlowTools/Tools/SiriAudioFlowTools.flowtool/SiriAudioFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x63178` | `0x6301c` | **`-0x15c`** |
| `__TEXT.__oslogstring` | `0x3938` | `0x39b8` | **`+0x80`** |
| `__TEXT.__auth_stubs` | `0x18e0` | `0x1920` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x2708` | `0x2740` | **`+0x38`** |
| `__TEXT.__const` | `0x6d10` | `0x6d40` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0xc78` | `0xc98` | **`+0x20`** |
| `__TEXT.__cstring` | `0xa35` | `0xa55` | **`+0x20`** |
| `__DATA.__data` | `0x24c0` | `0x24c8` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x2110` | `0x2118` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x420` | `0x428` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x18bc` | `0x18c4` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1480` | `0x1488` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.33.2.0.0
+3600.33.6.0.0

-  Functions: 1656
+  Functions: 1658

-  CStrings:  309
+  CStrings:  311
CStrings:
+ "PlayAudioAppIntentExecutionStrategy.remapEntityToTargetApp() remapped=%{public}s local=%{private}s stable=%{private}s"
+ "passthrough .pair(local,stable)"
```
