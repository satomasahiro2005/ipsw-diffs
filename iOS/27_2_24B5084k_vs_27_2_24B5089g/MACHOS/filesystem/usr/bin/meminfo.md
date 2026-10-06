## meminfo

> `/usr/bin/meminfo`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x138a8` | `0x138f0` | **`+0x48`** |
| `__TEXT.__auth_stubs` | `0xb00` | `0xb10` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x588` | `0x590` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1071.40.6.0.0
+1071.40.9.0.0

-  Symbols:   290
+  Symbols:   291
Symbols:
+ _host_info
Functions:
~ sub_100005f70 : 3516 -> 3588
```
