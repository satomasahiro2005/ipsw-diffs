## srp-mdns-proxy

> `/usr/libexec/srp-mdns-proxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x8e75` | `0x8f27` | **`+0xb2`** |
| `__TEXT.__text` | `0x8b500` | `0x8b55c` | **`+0x5c`** |
| `__TEXT.__oslogstring` | `0x141ca` | `0x141b4` | **`-0x16`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3111.0.5.0.1
+3111.40.40.0.0

-  CStrings:  2700
+  CStrings:  2704
Symbols:
+ _thread_service_note_function
- _thread_service_note
Functions:
~ _dnssd_client_action_probing : 2984 -> 3000
~ _dnssd_client_service_unpublish : 80 -> 88
~ _thread_service_note -> _thread_service_note_function : 1168 -> 1132
~ _adv_ctl_start_thread_shutdown : 604 -> 620
~ _service_tracker_callback : 2972 -> 3000
~ _service_tracker_services_are_awaiting_removal : 256 -> 264
~ _service_publisher_have_competing_unicast_service : 484 -> 512
~ _service_publisher_anycast_service_present : 132 -> 144
~ _service_publisher_stale_service_present : 248 -> 264
~ _service_publisher_queue_run : 1440 -> 1448
~ _service_publisher_update_callback : 1660 -> 1648
CStrings:
+ "%{public}s: could not parse u32 (%u bytes were available)"
+ "21:32:25"
+ "Sep  4 2026"
+ "dnssd_client_service_unpublish"
+ "service_publisher_anycast_service_present"
+ "service_publisher_have_competing_unicast_service"
+ "service_publisher_stale_service_present"
+ "service_tracker_thread_service_note"
- "%{public}s: service TLV value must be at least 6 bytes long (was %u bytes long)"
- "18:55:30"
- "Aug  8 2026"
- "thread_service_note"
```
