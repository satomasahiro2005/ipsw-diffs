## libquic.dylib

> `/usr/lib/libquic.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xca734` | `0xcbf68` | **`+0x1834`** |
| `__TEXT.__oslogstring` | `0x1192b` | `0x11a0b` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x868b` | `0x86e0` | **`+0x55`** |
| `__AUTH_CONST.__auth_got` | `0xd98` | `0xda8` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x690` | `0x680` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0xcf8` | `0xd08` | **`+0x10`** |

### Other Changes

```diff

-6681.0.372.502.1
+6681.0.436.0.8

-  Functions: 1139
-  Symbols:   1636
-  CStrings:  2575
+  Functions: 1143
+  Symbols:   1642
+  CStrings:  2579
Symbols:
+ _nw_path_uses_interface_subtype
+ _nw_quic_connection_get_close_tls_after_handshake
+ _quic_conn_close_tls_flow
+ _quic_path_get_ifindex
+ _quic_path_unmark_lossy
+ _quic_recovery_declare_packet_lost
CStrings:
+ "%{public}s %{public}s [%{public}s-%{public}s] closing TLS stream after handshake"
+ "%{public}s %{public}s [%{public}s-%{public}s] keep-alive timer rearmed after probe failure, interval=%llu us"
+ "%{public}s %{public}s [%{public}s-%{public}s] keep-alive timer rearmed after send, interval=%llu us"
+ "invalid frame type encoding"
+ "quic_path_get_ifindex"
+ "quic_path_unmark_lossy"
+ "quic_recovery_declare_packet_lost"
- "%{public}s TLS connection not released"
- "%{public}s empty CID array"
- "MP_PROTOCOL_VIOLATION"
```
