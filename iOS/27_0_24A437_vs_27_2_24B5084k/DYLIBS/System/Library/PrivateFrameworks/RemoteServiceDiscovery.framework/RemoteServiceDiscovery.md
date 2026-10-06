## RemoteServiceDiscovery

> `/System/Library/PrivateFrameworks/RemoteServiceDiscovery.framework/RemoteServiceDiscovery`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf560` | `0xf660` | **`+0x100`** |
| `__TEXT.__cstring` | `0x135c` | `0x1398` | **`+0x3c`** |
| `__TEXT.__oslogstring` | `0x1d11` | `0x1d44` | **`+0x33`** |
| `__TEXT.__gcc_except_tab` | `0x3c0` | `0x3d8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x550` | `0x558` | **`+0x8`** |

### Other Changes

```diff

-245.0.7.0.0
+245.40.8.0.0

-  Functions: 504
-  Symbols:   742
-  CStrings:  355
+  Functions: 507
+  Symbols:   745
+  CStrings:  359
Symbols:
+ GCC_except_table0
+ GCC_except_table215
+ ___do_control_channel_request_with_override_block_invoke
+ _do_control_channel_request_with_override
+ _remote_control_connect_loopback_with_message_override
+ _remote_control_disconnect_loopback
- GCC_except_table211
- ___do_control_channel_request_block_invoke
- _do_control_channel_request
CStrings:
+ "connect_loopback_with_override"
+ "disconnect_loopback"
+ "override"
+ "remote_socket_poll_connect_async: NULL reply_queue"
```
