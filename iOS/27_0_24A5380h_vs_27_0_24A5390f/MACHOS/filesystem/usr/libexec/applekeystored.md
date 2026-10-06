## applekeystored

> `/usr/libexec/applekeystored`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9d6e0` | `0x9d854` | **`+0x174`** |
| `__TEXT.__const` | `0x9d99` | `0x9de9` | **`+0x50`** |
| `__DATA.__data` | `0x72d8` | `0x7300` | **`+0x28`** |
| `__TEXT.__cstring` | `0xfe3c` | `0xfe5c` | **`+0x20`** |
| `__DATA_CONST.__const` | `0xea68` | `0xea58` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2383.0.14.0.1
+2383.0.22.0.2

-  Functions: 3301
+  Functions: 3303

-  CStrings:  2636
+  CStrings:  2637
CStrings:
+ "aks_get_convenience_bio_state"
```
