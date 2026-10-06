## srp-mdns-proxy

> `/usr/libexec/srp-mdns-proxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8b4f4` | `0x8b500` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff
Functions:
~ _state_machine_event_create : 772 -> 776
~ _dns_concatenate_name_to_wire_ : 868 -> 872
~ _dns_name_print_to_limit : 356 -> 360
CStrings:
+ "18:55:30"
- "22:10:54"
```
