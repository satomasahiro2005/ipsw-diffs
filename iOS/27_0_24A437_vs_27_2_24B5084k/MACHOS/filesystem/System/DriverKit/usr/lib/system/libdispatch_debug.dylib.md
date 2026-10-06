## libdispatch_debug.dylib

> `/System/DriverKit/usr/lib/system/libdispatch_debug.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbb96c` | `0xbba8c` | **`+0x120`** |
| `__TEXT.__unwind_info` | `0x8c8` | `0x8d0` | **`+0x8`** |

### Same-size Content Changes

- `__AUTH.__data`
- `__AUTH_CONST.__auth_got`
- `__AUTH_CONST.__const`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__dof_dispatch`
- `__TEXT.__dof_voucher`

### Other Changes

```diff

-1605.0.2.0.0
+1605.40.4.0.0

-  Functions: 1170
-  Symbols:   1589
+  Functions: 1171
+  Symbols:   1590
Symbols:
+ _firehose_mach_port_allocate_connection_port
Functions:
~ _firehose_client_reconnect : 3004 -> 3048
+ _firehose_mach_port_allocate_connection_port
```
