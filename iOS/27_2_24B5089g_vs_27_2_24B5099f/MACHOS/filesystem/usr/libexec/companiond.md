## companiond

> `/usr/libexec/companiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8c09c` | `0x8c068` | **`-0x34`** |
| `__DATA.__data` | `0x1e10` | `0x1df0` | **`-0x20`** |
| `__DATA_CONST.__got` | `0xd00` | `0xcf8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-524.10.94.0.0
+524.10.109.0.1

-  Symbols:   1270
+  Symbols:   1269
Symbols:
+ _$s10Foundation4DateV2leoiySbAC_ACtFZ
- _$s10Foundation4DateVSLAAMc
- _$sSL2leoiySbx_xtFZTj
Functions:
~ sub_1000398c0 : 3004 -> 2944
~ sub_10005bbf0 -> sub_10005bbb4 : 108 -> 112
~ sub_100071474 -> sub_10007143c : 108 -> 112
```
