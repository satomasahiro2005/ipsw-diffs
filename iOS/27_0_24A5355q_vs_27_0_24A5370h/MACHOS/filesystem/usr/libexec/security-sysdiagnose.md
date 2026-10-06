## security-sysdiagnose

> `/usr/libexec/security-sysdiagnose`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3dcc` | `0x3de0` | **`+0x14`** |
| `__TEXT.__const` | `0x70` | `0x68` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-62426.0.0.0.4
+62460.0.22.0.0
Functions:
~ sub_100000e08 : 268 -> 280
~ sub_100000f14 -> sub_100000f20 : 448 -> 444
~ sub_1000013a8 -> sub_1000013b0 : 6372 -> 6368
~ sub_100002f1c -> sub_100002f20 : 716 -> 708
~ sub_1000032b4 -> sub_1000032b0 : 836 -> 848
~ sub_1000043c4 -> sub_1000043cc : 588 -> 600
```
