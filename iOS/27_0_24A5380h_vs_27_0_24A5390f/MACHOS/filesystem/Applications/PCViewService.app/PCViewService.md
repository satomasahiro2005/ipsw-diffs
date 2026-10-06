## PCViewService

> `/Applications/PCViewService.app/PCViewService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8ba0c` | `0x8b9c4` | **`-0x48`** |
| `__DATA.__data` | `0x8770` | `0x8740` | **`-0x30`** |
| `__TEXT.__cstring` | `0x2a60` | `0x2a30` | **`-0x30`** |
| `__TEXT.__objc_methname` | `0x554f` | `0x551f` | **`-0x30`** |
| `__TEXT.__swift5_reflstr` | `0x39bf` | `0x398f` | **`-0x30`** |
| `__DATA.__objc_const` | `0x6890` | `0x6870` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0x553c` | `0x551c` | **`-0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x3128` | `0x311c` | **`-0xc`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-376.0.10.0.0
+376.0.14.0.0

-  CStrings:  1459
+  CStrings:  1457
Functions:
~ sub_10003e130 : 1552 -> 1544
~ sub_10003eb94 -> sub_10003eb8c : 14944 -> 14880
CStrings:
- "_requireEligibleForUserSessionAlways"
- "requireEligibleForUserSessionAlways"
```
