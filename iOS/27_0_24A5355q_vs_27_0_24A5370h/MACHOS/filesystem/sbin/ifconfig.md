## ifconfig

> `/sbin/ifconfig`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbbf4` | `0xbc94` | **`+0xa0`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ _bond_status : 744 -> 772
~ _bond_ctor : 84 -> 100
~ _ifconfig_ctor : 52 -> 60
~ _netem_parse_args : 1284 -> 1356
~ _ifmedia_ctor : 84 -> 100
~ _setmedia : 368 -> 376
~ _domediaopt : 484 -> 492
~ _print_media_word : 468 -> 476
~ _get_subtype_desc : 96 -> 112
~ _vlan_ctor : 108 -> 124
~ _inet6_ctor : 96 -> 112
~ _bridge_ctor : 84 -> 100
~ _bridge_addresses : 492 -> 480
~ _bridge_status : 3368 -> 3296
~ _clone_ctor : 84 -> 100
```
