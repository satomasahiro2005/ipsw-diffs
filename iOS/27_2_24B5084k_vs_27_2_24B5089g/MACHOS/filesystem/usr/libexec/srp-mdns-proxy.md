## srp-mdns-proxy

> `/usr/libexec/srp-mdns-proxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8b55c` | `0x8b630` | **`+0xd4`** |
| `__TEXT.__oslogstring` | `0x141b4` | `0x1423e` | **`+0x8a`** |
| `__TEXT.__unwind_info` | `0x638` | `0x630` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-3111.40.40.0.0
+3111.40.42.0.0

-  CStrings:  2704
+  CStrings:  2705
Functions:
~ _srp_mdns_cancel_previous_instance : 524 -> 536
~ _prepare_update : 22068 -> 22056
~ _register_instance : 1680 -> 1684
~ _instance_vec_txns_forget : 368 -> 576
CStrings:
+ "%{public}s: forgetting previous sdref %p on %{public}s %p %{private, mask.hash}s instance %{private, mask.hash}s . %{private, mask.hash}s"
+ "08:59:03"
+ "Sep 12 2026"
- "21:32:25"
- "Sep  4 2026"
```
