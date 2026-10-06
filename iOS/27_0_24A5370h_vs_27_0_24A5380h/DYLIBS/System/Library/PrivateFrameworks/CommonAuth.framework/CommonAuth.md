## CommonAuth

> `/System/Library/PrivateFrameworks/CommonAuth.framework/CommonAuth`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6678` | `0x6664` | **`-0x14`** |

### Other Changes

```diff

-725.0.6.0.0
+725.0.8.0.0
Functions:
~ _heim_ntlm_unparse_flags -> _heim_ntlm_free_buf : 44 -> 48
~ _heim_ntlm_free_buf -> _heim_ntlm_free_targetinfo : 48 -> 108
~ _heim_ntlm_free_targetinfo -> _heim_ntlm_encode_targetinfo : 108 -> 536
~ _heim_ntlm_encode_targetinfo -> _encode_ti_string : 536 -> 120
~ _encode_ti_string -> _heim_ntlm_decode_targetinfo : 120 -> 496
~ _heim_ntlm_decode_targetinfo -> sub_257136bd0 : 496 -> 44
~ _heim_digest_parse_challenge : 352 -> 356
~ _heim_digest_parse_response : 656 -> 660
~ _heim_digest_get_key : 116 -> 124
~ _heim_digest_set_key : 420 -> 428
~ _unparse_something : 264 -> 248
~ _rk_strlwr : 80 -> 64
~ _wind_ucs2read : 272 -> 260
```
