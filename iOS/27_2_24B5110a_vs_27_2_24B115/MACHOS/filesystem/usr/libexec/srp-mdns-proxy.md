## srp-mdns-proxy

> `/usr/libexec/srp-mdns-proxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8b630` | `0x8baa4` | **`+0x474`** |
| `__TEXT.__oslogstring` | `0x1423e` | `0x144a4` | **`+0x266`** |
| `__TEXT.__cstring` | `0x8f27` | `0x8fde` | **`+0xb7`** |
| `__TEXT.__unwind_info` | `0x630` | `0x648` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-  Functions: 489
-  Symbols:   1184
-  CStrings:  2705
+  Functions: 493
+  Symbols:   1188
+  CStrings:  2712
Symbols:
+ _thread_netdata_decode_6lowpan_id_payload
+ _thread_netdata_decode_prefix_payload
+ _thread_netdata_decode_server_payload
+ _thread_netdata_decode_service_payload
CStrings:
+ "%{public}s: TLV length %zu exceeds the %d byte maximum"
+ "%{public}s: dns_concatenate_name_to_wire: called at %{public}s:%d with both prefix and labels_prefix non-NULL (labels_prefix = %p, prefix = %p, suffix = %p)"
+ "%{public}s: dns_concatenate_name_to_wire: called at %{public}s:%d with both suffix and labels_prefix including a terminal label (labels_prefix = %p, prefix = %p, suffix = %p)"
+ "%{public}s: dns_concatenate_name_to_wire: called at %{public}s:%d with no way to terminate the name (labels_prefix = %p, prefix = %p, suffix = %p)"
+ "%{public}s: service TLV value must be at least 6 bytes long (was %u bytes long)"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/mDNSResponderExtras/ServiceRegistration/wireutils.c"
+ "23:59:01"
+ "Oct  7 2026"
+ "dns_concatenate_name_to_wire_"
- "02:05:20"
- "Oct  4 2026"
```
