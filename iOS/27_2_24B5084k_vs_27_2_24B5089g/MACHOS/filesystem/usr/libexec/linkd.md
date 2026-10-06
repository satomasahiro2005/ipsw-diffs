## linkd

> `/usr/libexec/linkd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x1bb5` | `0x1c15` | **`+0x60`** |
| `__TEXT.__text` | `0xca3bc` | `0xca3f4` | **`+0x38`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-301.1.9.1.101
+301.1.10.2.101

-  CStrings:  1229
+  CStrings:  1232
Functions:
~ sub_100017678 : 20 -> 32
~ sub_1000c4e3c -> sub_1000c4e48 : 120 -> 164
CStrings:
+ "preConfirmationClientHydration"
+ "preConfirmationEntityHydration"
+ "preConfirmationEntityQuery"
```
