## icloudwebd

> `/usr/libexec/icloudwebd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x69244` | `0x69450` | **`+0x20c`** |
| `__DATA_CONST.__const` | `0x60c0` | `0x60e8` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x202f` | `0x2019` | **`-0x16`** |
| `__DATA.__data` | `0x1f10` | `0x1f00` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x5b8` | `0x5a8` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x838` | `0x848` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1c60` | `0x1c58` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
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

-70.0.0.0.0
+71.1.0.0.0

-  Functions: 2275
-  Symbols:   839
+  Functions: 2274
+  Symbols:   837
Symbols:
+ _$s10Foundation4DataV15_RepresentationO6append10contentsOfySW_tF
- _$s10Foundation15ContiguousBytesMp
- _$s10Foundation4DataV15_RepresentationO15replaceSubrange_4with5countySnySiG_SVSgSitF
- _$ss15CollectionOfOneVMn
```
