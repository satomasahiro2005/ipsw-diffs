## RemoteXPC

> `/System/Library/PrivateFrameworks/RemoteXPC.framework/RemoteXPC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdf34` | `0xdfa4` | **`+0x70`** |
| `__AUTH_CONST.__objc_const` | `0xf28` | `0xf48` | **`+0x20`** |
| `__TEXT.__const` | `0x90` | `0x98` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x290` | `0x288` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x124` | `0x128` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-3298.2.1.0.0
+3298.40.20.0.0

-  Functions: 168
-  Symbols:   515
+  Functions: 169
+  Symbols:   517
Symbols:
+ GCC_except_table120
+ GCC_except_table55
+ GCC_except_table84
+ GCC_except_table96
+ _OBJC_IVAR_$_OS_xpc_remote_connection.connected_device
+ _xpc_remote_connection_copy_remote_device
- GCC_except_table119
- GCC_except_table54
- GCC_except_table83
- GCC_except_table95
Functions:
~ -[OS_xpc_remote_connection .cxx_destruct] : 272 -> 284
~ _xpc_remote_connection_create_with_remote_service : 424 -> 432
+ _xpc_remote_connection_copy_remote_device
~ ____xpc_remote_connection_listen_block_invoke : 908 -> 924
```
