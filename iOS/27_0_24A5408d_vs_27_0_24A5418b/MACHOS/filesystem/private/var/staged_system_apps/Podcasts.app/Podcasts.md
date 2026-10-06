## Podcasts

> `/private/var/staged_system_apps/Podcasts.app/Podcasts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ea50c` | `0x3eb048` | **`+0xb3c`** |
| `__TEXT.__cstring` | `0x1116a` | `0x1128a` | **`+0x120`** |
| `__DATA_CONST.__const` | `0x1c800` | `0x1c850` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x11736` | `0x1176c` | **`+0x36`** |
| `__TEXT.__swift5_capture` | `0x6924` | `0x694c` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0xca18` | `0xca30` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
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

-4027.110.1.0.0
+4027.110.2.0.0

-  Functions: 18116
+  Functions: 18122

-  CStrings:  14232
+  CStrings:  14235
CStrings:
+ "Manual download prefers video but episode %{public}s has no video variant — falling back to audio download"
+ "Starting download for episode %{public}s: media: %{public}s, isFromSaving: %{public}s, forcedPreflight: %{public}s"
+ "Video upgrade skipped for %{public}s — video already present"
+ "Video upgrade skipped for %{public}s — video unavailable"
- "Video upgrade skipped for %{public}s — video already present or unavailable"
```
