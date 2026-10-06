## srp-mdns-proxy

> `/usr/libexec/srp-mdns-proxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8b3bc` | `0x8b4f4` | **`+0x138`** |
| `__TEXT.__oslogstring` | `0x1411d` | `0x141ca` | **`+0xad`** |
| `__TEXT.__const` | `0x2d5` | `0x2e5` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3089.0.0.0.1
+3109.0.0.0.0

-  CStrings:  2698
+  CStrings:  2700
Functions:
~ _dso_state_create : 536 -> 556
~ _dns_proxy_input_for_server : 9384 -> 9620
~ _dp_query_send_dns_response : 9004 -> 9036
~ _srp_update_start : 7956 -> 7980
CStrings:
+ "%{public}s: [DSO%u] Fatal: sizeof (*dso)[%zu], outsize[%zu], namespace[%zu]"
+ "%{public}s: dso_message_received: fatal: %s sent %ld byte message, QR=0, xid=%02x%02x"
+ "%{public}s: dso_message_received: fatal: %s: too many additional TLVs: %ld %ld"
+ "02:42:50"
+ "Jul 10 2026"
- "%{public}s: Fatal: sizeof (*dso)[%zu], outsize[%zu], namespace[%zu]"
- "00:32:02"
- "Jun 25 2026"
```
