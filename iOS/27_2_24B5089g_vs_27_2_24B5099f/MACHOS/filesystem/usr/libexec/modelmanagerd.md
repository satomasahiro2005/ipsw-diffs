## modelmanagerd

> `/usr/libexec/modelmanagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c4f34` | `0x1c59d0` | **`+0xa9c`** |
| `__TEXT.__eh_frame` | `0x17174` | `0x1723c` | **`+0xc8`** |
| `__TEXT.__unwind_info` | `0x7100` | `0x7158` | **`+0x58`** |
| `__TEXT.__auth_stubs` | `0x3f50` | `0x3f80` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x1fb0` | `0x1fc8` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0xd78` | `0xd70` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-714.40.84.502.1
+714.40.86.0.0

-  Functions: 9393
-  Symbols:   1722
+  Functions: 9446
+  Symbols:   1725
Symbols:
+ _$s10Foundation4DateV2geoiySbAC_ACtFZ
+ _$s10Foundation4DateV2leoiySbAC_ACtFZ
+ _swift_retain_x13
```
