## adc-silenus-v5x.im4p

> `Firmware/isp_bni/adc-silenus-v5x.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x8b7990` | `0x8b7b10` | **`+0x180`** |
| `__DATA.__const` | `0x62b98` | `0x62c58` | **`+0xc0`** |
| `__TEXT.__text` | `0xb5b84c` | `0xb5b904` | **`+0xb8`** |
| `__TEXT.__cstring` | `0xaf116` | `0xaf1c0` | **`+0xaa`** |

### Same-size Content Changes

- `__DATA.__chain_starts`
- `__DATA.__data`
- `__DATA.__data_copy`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`
- `__DATA._rtk_patchbay`
- `__DATA._rtk_power`
- `__TEXT.__eh_frame`

### Other Changes

```diff

-  CStrings:  19046
+  CStrings:  19050
Functions:
~ sub_58a278 : 856 -> 908
~ sub_58d7a4 -> sub_58d7d8 : 15252 -> 15272
~ sub_591b9c -> sub_591be4 : 404 -> 428
~ sub_591d30 -> sub_591d90 : 1492 -> 1504
~ sub_5949e8 -> sub_594a54 : 2080 -> 2108
~ sub_62b274 -> sub_62b2fc : 2828 -> 2876
~ sub_b5b714 -> sub_b5b7cc : 320 -> 312
CStrings:
+ "02:33:38"
+ "NVM header revision invalid %d - off %d\n"
+ "transition_mode019_to_mode550_revert_step0"
+ "transition_mode019_to_mode550_revert_step1"
+ "transition_mode019_to_mode550_step0"
+ "transition_mode019_to_mode550_step1"
- "21:29:55"
- "NVM header revision invalid\n"
```
