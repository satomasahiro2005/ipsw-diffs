## captiveagent

> `/usr/libexec/captiveagent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_stubs` | `0x16a0` | `0x1720` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x500` | `0x4b0` | **`-0x50`** |
| `__TEXT.__text` | `0x10758` | `0x107a8` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0xb50` | `0xb60` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x5c0` | `0x5c8` | **`+0x8`** |
| `__TEXT.__const` | `0x13e` | `0x146` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-541.0.0.0.0
+542.0.0.0.1

-  Symbols:   254
+  Symbols:   255
Symbols:
+ _objc_retainBlock
Functions:
~ sub_100001494 : 228 -> 224
~ sub_100001578 -> sub_100001574 : 88 -> 100
~ sub_1000015d0 -> sub_1000015d8 : 384 -> 380
~ sub_100001750 -> sub_100001754 : 564 -> 560
~ sub_100001984 : 264 -> 252
~ sub_100001a8c -> sub_100001a80 : 204 -> 192
~ sub_100001b58 -> sub_100001b40 : 548 -> 544
~ sub_100001d7c -> sub_100001d60 : 548 -> 540
~ sub_100002288 -> sub_100002264 : 128 -> 140
~ sub_10000353c -> sub_100003524 : 3220 -> 3248
~ sub_100004e14 -> sub_100004e18 : 80 -> 96
~ sub_1000052a0 -> sub_1000052b4 : 152 -> 164
~ sub_100007dac -> sub_100007dcc : 144 -> 156
~ sub_100010ae8 -> sub_100010b14 : 64 -> 88
~ sub_100010b28 -> sub_100010b6c : 152 -> 164
```
