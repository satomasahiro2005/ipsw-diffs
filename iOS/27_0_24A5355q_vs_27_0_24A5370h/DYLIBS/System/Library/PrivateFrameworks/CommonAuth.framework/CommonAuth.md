## CommonAuth

> `/System/Library/PrivateFrameworks/CommonAuth.framework/CommonAuth`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x65f0` | `0x6678` | **`+0x88`** |
| `__TEXT.__const` | `0x154` | `0x15c` | **`+0x8`** |

### Other Changes

```diff

-720.0.0.0.0
+725.0.6.0.0
Functions:
~ _ret_string : 356 -> 352
~ _ascii2ucs2le : 400 -> 404
~ _heim_cram_md5_export : 404 -> 408
~ _heim_digest_get_key : 100 -> 116
~ _heim_digest_set_key : 404 -> 420
~ __krb5_put_int : 44 -> 40
~ __krb5_get_int : 40 -> 56
~ _encode_hex : 168 -> 180
~ _rk_hex_decode : 176 -> 196
~ _pos : 80 -> 76
~ _unparse_something : 248 -> 264
~ _rk_strlwr : 64 -> 80
~ _ct_memcmp : 52 -> 60
~ _wind_ucs2read : 260 -> 272
~ _wind_utf8ucs2 : 188 -> 184
~ _wind_ucs2utf8 : 176 -> 188
```
