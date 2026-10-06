## rans.t8140.release.im4p

> `Firmware/rans.t8140.release.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e53fc` | `0x1e5b5c` | **`+0x760`** |
| `__TEXT.__cstring` | `0x25172` | `0x25373` | **`+0x201`** |
| `__DATA.__const` | `0x2420` | `0x2450` | **`+0x30`** |
| `__DATA.__data` | `0x5bf8` | `0x5c00` | **`+0x8`** |

### Same-size Content Changes

- `__DATA._rtk_mtab`
- `__DATA._rtk_patchbay`
- `__TEXT.__const`

### Other Changes

```diff

-  Functions: 1970
+  Functions: 1976

-  CStrings:  3961
+  CStrings:  3965
CStrings:
+ "241.0.12"
+ "241.0.12~425"
+ "AppleStorageFirmwareASP3-241.0.12~425"
+ "{ 'trace_id': 'CACHE_EVICT', 'tp_func': %d, 'timestamp': %llu, 'todo': %u, 'dirty': %u, 'evict': %u, 'hostq': %u }\n"
+ "{ 'trace_id': 'PUSH_FLOW_PICK', 'tp_func': %d, 'timestamp': %llu, 'flow': %u, 'writeq': %u, 'thresh': %u, 'reason': %u }\n"
+ "{ 'trace_id': 'PUSH_FLOW_PICK_PREV', 'tp_func': %d, 'timestamp': %llu, 'flow': %u, 'writeq': %u, 'thresh': %u, 'reason': %u }\n"
+ "{ 'trace_id': 'PUSH_FLOW_TOPUP', 'tp_func': %d, 'timestamp': %llu, 'oldFlow': %u, 'writeq': %u, 'stripe': %u, 'moved': %u }\n"
+ "{ 'trace_id': 'PUSH_HOST_STALL', 'tp_func': %d, 'timestamp': %llu, 'flow': %u, 'writeq': %u, 'hostq': %u, 'secleft': %u }\n"
- "241.0.6"
- "241.0.6~137"
- "AppleStorageFirmwareASP3-241.0.6~137"
- "{ 'trace_id': 'CACHE_EVICT', 'tp_func': %d, 'timestamp': %llu, 'todo': %u, 'dirty': %u, 'evict': %u }\n"
```
