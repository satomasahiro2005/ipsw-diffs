## BiomeFoundation

> `/System/Library/PrivateFrameworks/BiomeFoundation.framework/BiomeFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34bbc` | `0x34cb0` | **`+0xf4`** |
| `__TEXT.__oslogstring` | `0x33c2` | `0x341f` | **`+0x5d`** |
| `__TEXT.__objc_methlist` | `0x2a74` | `0x2aa4` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x18d0` | `0x18f8` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x708` | `0x710` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0xdf4` | `0xdfc` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xef8` | `0xf00` | **`+0x8`** |

### Other Changes

```diff

-255.0.2.0.0
+256.0.1.0.0

-  Functions: 1232
-  Symbols:   2203
+  Functions: 1236
+  Symbols:   2206
Symbols:
+ +[BMXPCConnectionFactory connectionToAccessServerInDomain:user:useCase:options:callerConnection:]
+ -[BMAccessClient _newConnectionForDomain:callerConnection:]
+ -[BMAccessClient _requestAccessToResource:mode:callerConnection:error:]
+ -[BMAccessClient _synchronousRemoteObjectProxyForDomain:callerConnection:errorHandler:]
+ -[BMAccessClient requestAccessToResource:mode:callerConnection:error:]
+ -[BMXPCConnectionFactory _newConnectionWithCallerConnection:]
+ -[BMXPCConnectionFactory _newConnectionWrapperWithCallerConnection:]
+ -[BMXPCConnectionFactory _proxyConnectionThroughCaller:]
+ -[BMXPCConnectionFactory initWithServiceType:domain:user:useCase:options:]
+ GCC_except_table14
+ GCC_except_table24
+ ___56-[BMXPCConnectionFactory _proxyConnectionThroughCaller:]_block_invoke
+ ___68-[BMXPCConnectionFactory _newConnectionWrapperWithCallerConnection:]_block_invoke
+ ___68-[BMXPCConnectionFactory _newConnectionWrapperWithCallerConnection:]_block_invoke_2
+ ___71-[BMAccessClient _requestAccessToResource:mode:callerConnection:error:]_block_invoke
+ ___87-[BMAccessClient _synchronousRemoteObjectProxyForDomain:callerConnection:errorHandler:]_block_invoke
+ ___block_descriptor_48_e8_32s40s_e29_"BMXPCConnectionWrapper"8?0ls32l8s40l8
+ _objc_retain_x6
- -[BMAccessClient _newConnectionForDomain:]
- -[BMXPCConnectionFactory _newConnection]
- -[BMXPCConnectionFactory _requestConnectionFromCaller]
- -[BMXPCConnectionFactory initWithType:domain:user:useCase:options:]
- -[BMXPCConnectionFactory makeConnectionWrapper]
- GCC_except_table11
- GCC_except_table18
- GCC_except_table25
- GCC_except_table42
- ___47-[BMXPCConnectionFactory makeConnectionWrapper]_block_invoke
- ___47-[BMXPCConnectionFactory makeConnectionWrapper]_block_invoke_2
- ___53-[BMAccessClient requestAccessToResource:mode:error:]_block_invoke
- ___54-[BMXPCConnectionFactory _requestConnectionFromCaller]_block_invoke
- ___70-[BMAccessClient _synchronousRemoteObjectProxyForDomain:errorHandler:]_block_invoke
- ___block_descriptor_40_e8_32s_e29_"BMXPCConnectionWrapper"8?0ls32l8
CStrings:
+ "Unable to determine caller connection for on-behalf-of proxy: no explicit callerConnection was supplied and NSXPCConnection.currentConnection is nil"
- "Unable to determine current connection in write service"
```
