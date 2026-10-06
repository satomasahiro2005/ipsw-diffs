## libheimdal-asn1.dylib

> `/usr/lib/libheimdal-asn1.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__data` | `—` | `0x390` | **`+0x390`** |
| `__DATA_DIRTY.__data` | `0x390` | `—` | **`-0x390`** |
| `__TEXT.__text` | `0x4910` | `0x48cc` | **`-0x44`** |

### Other Changes

```diff

-725.0.6.0.0
+725.0.8.0.0
Functions:
~ _der_get_oid : 324 -> 332
~ _der_get_general_string : 228 -> 232
~ _der_put_length_and_tag : 208 -> 196
~ _der_put_tag : 176 -> 164
~ _der_put_unsigned : 116 -> 108
~ _der_put_oid : 216 -> 196
~ _der_put_integer : 204 -> 188
~ _der_put_length : 128 -> 116
```
