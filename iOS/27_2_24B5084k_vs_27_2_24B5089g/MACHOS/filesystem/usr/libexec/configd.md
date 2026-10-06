## configd

> `/usr/libexec/configd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x68fac` | `0x68fcc` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x24d0` | `0x24e0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1278` | `0x1280` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1452.0.0.0.0
+1453.0.0.0.0

-  Symbols:   818
+  Symbols:   819
Symbols:
+ _nw_resolver_config_set_interface_name
Functions:
~ sub_1000516e0 : 544 -> 576
```
