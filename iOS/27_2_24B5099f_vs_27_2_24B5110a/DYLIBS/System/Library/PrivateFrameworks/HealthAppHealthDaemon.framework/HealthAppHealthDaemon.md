## HealthAppHealthDaemon

> `/System/Library/PrivateFrameworks/HealthAppHealthDaemon.framework/HealthAppHealthDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4972c` | `0x49a10` | **`+0x2e4`** |
| `__DATA_CONST.__const` | `0x690` | `0x728` | **`+0x98`** |
| `__TEXT.__cstring` | `0x1855` | `0x18e5` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x1ee0` | `0x1f60` | **`+0x80`** |
| `__AUTH_CONST.__cfstring` | `0x900` | `0x960` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0x3220` | `0x3280` | **`+0x60`** |
| `__DATA.__data` | `0x1100` | `0x1160` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x1598` | `0x1558` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x1498` | `0x14c8` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x10f0` | `0x1100` | **`+0x10`** |
| `__DATA.__bss` | `0x1e10` | `0x1e20` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x138` | `0x148` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x124` | `0x11c` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x878` | `0x880` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x158` | `0x160` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1490` | `0x1488` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-7027.1.54.2.3
+7027.1.56.2.9

-  Functions: 1681
-  Symbols:   1530
-  CStrings:  319
+  Functions: 1688
+  Symbols:   1552
+  CStrings:  324
Symbols:
+ +[HDHAHealthAppPluginHostConnection sharedConnection]
+ -[HDHAHealthAppPluginHostConnection connectionInvalidated]
+ -[HDHAHealthAppPluginHostConnection exportedInterface]
+ -[HDHAHealthAppPluginHostConnection remoteInterface]
+ -[HDHAHealthAppPluginHostConnection withProxy:]
+ -[HDHealthAppProfileExtension _notifyPluginHostIfDatabaseWasRecreated:]
+ _OBJC_CLASS_$_HKDaemonConnection
+ _OBJC_CLASS_$_HKDaemonProxyProvider
+ _OBJC_IVAR_$_HDHAHealthAppPluginHostConnection._proxyProvider
+ _OUTLINED_FUNCTION_4
+ __OBJC_$_CLASS_METHODS_HDHAHealthAppPluginHostConnection
+ __OBJC_$_PROP_LIST_HDHAHealthAppPluginHostConnection
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT__HKXPCExportable
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS__HKXPCExportable
+ __OBJC_$_PROTOCOL_METHOD_TYPES__HKXPCExportable
+ __OBJC_$_PROTOCOL_REFS__HKXPCExportable
+ __OBJC_CLASS_PROTOCOLS_$_HDHAHealthAppPluginHostConnection
+ __OBJC_LABEL_PROTOCOL_$__HKXPCExportable
+ __OBJC_PROTOCOL_$__HKXPCExportable
+ ___47-[HDHAHealthAppPluginHostConnection withProxy:]_block_invoke
+ ___47-[HDHAHealthAppPluginHostConnection withProxy:]_block_invoke_2
+ ___53+[HDHAHealthAppPluginHostConnection sharedConnection]_block_invoke
+ ___53-[HDHAHealthAppPluginHostConnection synchronousProxy]_block_invoke_2
+ ___67-[HDHAHealthPluginHostFeedGenerator handleJournaledSharingEntries:]_block_invoke_2
+ ___block_descriptor_40_e5_v8?0l
+ ___block_descriptor_40_e8_32bs_e8_v16?08ls32l8
+ ___block_descriptor_40_e8_32r_e8_v16?08lr32l8
+ ___block_descriptor_40_e8_32s_e33_v16?0"<HKHealthAppPluginHost>"8ls32l8
+ _dispatch_once
+ _objc_release_x1
+ _sharedConnection.onceToken
+ _sharedConnection.sharedConnection
- -[HDHAHealthAppPluginHostConnection dealloc]
- -[HDHAHealthAppPluginHostConnection proxy]
- -[HDHAHealthAppPluginHostConnection resumeIfNecessary]
- -[HDHAHealthPluginHostFeedGenerator healthAppPluginHost]
- _OBJC_CLASS_$_NSXPCConnection
- _OBJC_IVAR_$_HDHAHealthAppPluginHostConnection._connection
- _OBJC_IVAR_$_HDHAHealthAppPluginHostConnection._lock
- _OBJC_IVAR_$_HDHAHealthAppPluginHostConnection._resumed
- ___42-[HDHAHealthAppPluginHostConnection proxy]_block_invoke
- ___54-[HDHAHealthAppPluginHostConnection resumeIfNecessary]_block_invoke
CStrings:
+ "Could not read the Health database identifier: %{public}@"
+ "Health database was recreated, running background generation"
+ "HealthAppHealthDaemon.LastReadyDatabaseIdentifier"
+ "com.apple.healthappd.launch"
+ "com.apple.healthappd.pluginhost"
+ "v16@?0@\"<HKHealthAppPluginHost>\"8"
+ "v16@?0@8"
- "HDHAHealthAppPluginHostConnection remote proxy interrupted"
- "HDHAHealthAppPluginHostConnection remote proxy invalidated"
```
