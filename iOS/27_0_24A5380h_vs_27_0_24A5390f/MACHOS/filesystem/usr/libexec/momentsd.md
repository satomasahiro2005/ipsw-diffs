## momentsd

> `/usr/libexec/momentsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2625c0` | `0x262534` | **`-0x8c`** |
| `__DATA_CONST.__cfstring` | `0x26840` | `0x26820` | **`-0x20`** |
| `__DATA_CONST.__objc_intobj` | `0x3900` | `0x3918` | **`+0x18`** |
| `__TEXT.__cstring` | `0x2798e` | `0x2797e` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-415.0.0.0.0
+416.0.0.0.0
Functions:
~ -[NSArray(MOExtensions) getDurationOfMOEventArray] : 204 -> 240
~ -[MORoutineServiceManager _fetchEarliestVisitDateInRoutineWithHandler:] : 672 -> 676
~ ___71-[MORoutineServiceManager _fetchEarliestVisitDateInRoutineWithHandler:]_block_invoke : 748 -> 568
```
