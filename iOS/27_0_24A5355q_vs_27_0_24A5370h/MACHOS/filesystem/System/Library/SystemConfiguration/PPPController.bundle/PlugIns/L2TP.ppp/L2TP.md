## L2TP

> `/System/Library/SystemConfiguration/PPPController.bundle/PlugIns/L2TP.ppp/L2TP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xeca4` | `0xeccc` | **`+0x28`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1027.0.0.0.0
+1029.0.0.0.0
Functions:
~ sub_e24 : 1864 -> 1892
~ sub_3da4 -> sub_3dc0 : 6228 -> 6220
~ sub_6124 -> sub_6138 : 148 -> 140
~ _pfkey_send_register : 240 -> 236
~ _pfkey_align : 244 -> 240
~ _get_src_address : 1120 -> 1116
~ _IPSecCreateCiscoDefaultConfiguration : 2884 -> 2920
~ sub_ec2c -> sub_ec50 : 436 -> 440
```
