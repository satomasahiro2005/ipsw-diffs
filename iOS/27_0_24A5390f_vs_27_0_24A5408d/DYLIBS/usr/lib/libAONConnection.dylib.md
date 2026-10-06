## libAONConnection.dylib

> `/usr/lib/libAONConnection.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xab80` | `0xac88` | **`+0x108`** |
| `__TEXT.__cstring` | `0x1f3d` | `0x2033` | **`+0xf6`** |
| `__DATA_CONST.__const` | `0x328` | `0x348` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x240` | `0x248` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2b8` | `0x2c0` | **`+0x8`** |

### Other Changes

```diff

-251.0.7.0.0
+251.2.1.0.0

-  Functions: 206
-  Symbols:   366
-  CStrings:  225
+  Functions: 208
+  Symbols:   368
+  CStrings:  227
Symbols:
+ GCC_except_table147
+ __ZN22AONNetConnectionClient20onTransportConnectedEj
+ ____ZN4ULPN15TBClientAdaptor4initEP13tb_endpoint_sb_block_invoke_5
- GCC_except_table146
Functions:
+ __ZN22AONNetConnectionClient20onTransportConnectedEj
~ __ZN4ULPN15TBClientAdaptor4initEP13tb_endpoint_sb : 784 -> 860
+ ____ZN4ULPN15TBClientAdaptor4initEP13tb_endpoint_sb_block_invoke_5
~ ___aonnetworking_networkingservicecallback__server_start_owned_block_invoke : 2044 -> 2168
CStrings:
+ "TB_ASSERT: (server->transportconnected != ((void*)0)) && \"implementation for TransportConnected is not present\""
+ "v12@?0I8"
```
