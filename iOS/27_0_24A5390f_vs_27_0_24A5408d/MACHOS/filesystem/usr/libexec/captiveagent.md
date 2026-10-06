## captiveagent

> `/usr/libexec/captiveagent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x107a8` | `0x106ec` | **`-0xbc`** |
| `__TEXT.__auth_stubs` | `0xb60` | `0xb50` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x5c8` | `0x5c0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x468` | `0x470` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-  Symbols:   255
+  Symbols:   254
Symbols:
- _objc_retainBlock
Functions:
~ sub_100002264 : 140 -> 112
~ sub_100003524 -> sub_100003508 : 3248 -> 3220
~ sub_100004e18 -> sub_100004de0 : 96 -> 80
~ sub_1000052b4 -> sub_10000526c : 164 -> 136
~ sub_100007dcc -> sub_100007d68 : 156 -> 120
~ sub_100010b14 -> sub_100010a8c : 88 -> 64
~ sub_100010b6c -> sub_100010acc : 164 -> 136
```
