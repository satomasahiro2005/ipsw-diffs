## hybridsearchd

> `/usr/libexec/hybridsearchd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__auth_stubs` | `0x760` | `0x750` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x3b8` | `0x3b0` | **`-0x8`** |
| `__TEXT.__text` | `0x3870` | `0x3868` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-59.0.1.0.0
+62.1.0.0.0
Functions:
~ sub_1000034dc : 132 -> 124
```
