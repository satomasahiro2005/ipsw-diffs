## libbsm.0.dylib

> `/usr/lib/libbsm.0.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe8ec` | `0xe93c` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x2d8` | `0x2c8` | **`-0x10`** |

### Other Changes

```text
Functions:
~ _au_poltostr : 212 -> 232
~ _au_strtopol : 240 -> 244
~ _au_sflagstostr : 212 -> 232
~ _au_strtosflags : 240 -> 244
~ _getstrfromtype_locked : 364 -> 368
~ _au_domain_to_bsm : 52 -> 60
~ _au_bsm_to_domain : 68 -> 76
~ _fetch_arb_tok : 148 -> 144
~ _au_print_flags_tok : 17768 -> 17700
~ _print_string : 292 -> 288
~ _print_mem : 124 -> 140
~ _au_socket_type_to_bsm : 52 -> 60
~ _au_bsm_to_socket_type : 68 -> 76
~ _au_to_newgroups : 212 -> 220
~ _au_to_strings : 316 -> 324
~ _au_errno_to_bsm : 56 -> 64
~ _au_bsm_to_errno : 72 -> 80
~ _au_strerror : 76 -> 84
~ _au_fcntl_cmd_to_bsm : 52 -> 60
~ _au_bsm_to_fcntl_cmd : 68 -> 76
```
