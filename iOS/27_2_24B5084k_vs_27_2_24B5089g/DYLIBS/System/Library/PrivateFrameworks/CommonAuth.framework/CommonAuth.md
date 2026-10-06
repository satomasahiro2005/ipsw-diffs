## CommonAuth

> `/System/Library/PrivateFrameworks/CommonAuth.framework/CommonAuth`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0x77a` | `0x2a` | **`-0x750`** |
| `__DATA_DIRTY.__data` | `—` | `0x750` | **`+0x750`** |

### Other Changes

```text
Functions:
~ _heim_ntlm_free_buf -> _heim_ntlm_unparse_flags : 48 -> 44
~ _heim_ntlm_free_targetinfo -> _heim_ntlm_free_buf : 108 -> 48
~ _heim_ntlm_encode_targetinfo -> _heim_ntlm_free_targetinfo : 536 -> 108
~ _encode_ti_string -> _heim_ntlm_encode_targetinfo : 120 -> 536
~ _heim_ntlm_decode_targetinfo -> _encode_ti_string : 496 -> 120
~ sub_25c709bd0 -> _heim_ntlm_decode_targetinfo : 44 -> 496
```
