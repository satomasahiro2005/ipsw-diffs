## libxpc.dylib

> `/usr/lib/system/libxpc.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x52fe0` | `0x53050` | **`+0x70`** |
| `__TEXT.__cstring` | `0x7ce6` | `0x7d30` | **`+0x4a`** |
| `__DATA_CONST.__const` | `0x1e30` | `0x1e40` | **`+0x10`** |

### Other Changes

```diff

-3298.0.21.0.0
+3298.0.26.502.1

-  CStrings:  1295
+  CStrings:  1296
Functions:
~ __xpc_connection_init_recv_named : 1472 -> 1520
~ __xpc_connection_init_recv_anon : 256 -> 264
~ __xpc_connection_init_recv_port : 96 -> 116
~ __xpc_connection_derive_connection_port : 528 -> 564
~ __xpc_connection_init_send_named : 300 -> 292
~ __xpc_connection_init_send_anon : 256 -> 244
~ __xpc_connection_init_send_port : 96 -> 116
CStrings:
+ "An extension with the same bundle ID already exists with a different path"
```
