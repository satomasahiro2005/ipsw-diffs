## libheimdal-asn1.dylib

> `/usr/lib/libheimdal-asn1.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x48d8` | `0x4910` | **`+0x38`** |
| `__TEXT.__const` | `0xa8` | `0xb0` | **`+0x8`** |

### Other Changes

```diff

-720.0.0.0.0
+725.0.6.0.0
Functions:
~ __asn1_decode : 1896 -> 1944
~ _der_get_tag : 168 -> 164
~ _der_get_integer : 84 -> 80
~ __asn1_copy : 864 -> 836
~ _der_get_general_string : 236 -> 228
~ __asn1_encode : 1708 -> 1716
~ _der_put_length_and_tag : 204 -> 208
~ _der_put_tag : 172 -> 176
~ _der_put_heim_integer : 296 -> 292
~ _der_put_unsigned : 108 -> 116
~ __der_timegm : 452 -> 464
~ _der_print_heim_oid : 216 -> 212
~ _der_get_bmp_string : 260 -> 256
~ _der_get_universal_string : 256 -> 252
~ _der_put_integer : 172 -> 204
~ _der_put_length : 124 -> 128
~ _der_put_universal_string : 152 -> 136
~ _der_get_class_num : 96 -> 92
~ _der_get_type_num : 96 -> 92
~ _der_get_tag_num : 96 -> 92
~ __der_gmtime : 464 -> 460
~ _encode_hex : 168 -> 180
~ _rk_hex_decode : 176 -> 196
~ _pos : 80 -> 76
```
