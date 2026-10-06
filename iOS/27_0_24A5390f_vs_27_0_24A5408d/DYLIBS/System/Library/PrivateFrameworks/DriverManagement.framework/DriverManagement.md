## DriverManagement

> `/System/Library/PrivateFrameworks/DriverManagement.framework/DriverManagement`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a6fc` | `0x1b3b4` | **`+0xcb8`** |
| `__TEXT.__cstring` | `0xa15` | `0xb05` | **`+0xf0`** |
| `__AUTH_CONST.__objc_const` | `0x6c0` | `0x748` | **`+0x88`** |
| `__TEXT.__swift5_typeref` | `0x692` | `0x702` | **`+0x70`** |
| `__AUTH_CONST.__const` | `0xef8` | `0xf48` | **`+0x50`** |
| `__TEXT.__const` | `0x1af0` | `0x1b20` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x387` | `0x3a7` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x770` | `0x790` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x504` | `0x520` | **`+0x1c`** |
| `__TEXT.__objc_methlist` | `0x2b0` | `0x2c4` | **`+0x14`** |
| `__DATA.__data` | `0x2e8` | `0x2f8` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x60` | `0x70` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x7a0` | `0x7a8` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x18` | `0x20` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x10` | `0x18` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c0` | `0x1c8` | **`+0x8`** |
| `__DATA_DIRTY.__data` | `0x600` | `0x608` | **`+0x8`** |

### Other Changes

```diff

-514.0.0.0.0
+514.2.1.0.0

-  Functions: 742
-  Symbols:   423
-  CStrings:  56
+  Functions: 754
+  Symbols:   430
+  CStrings:  60
Symbols:
+ -[DriverManager driverApprovalStatesForCurrentAppWithError:]
+ __PROTOCOL_INSTANCE_METHODS__TtP16DriverManagement32DriverKitDaemonAppClientProtocol_
+ __PROTOCOL_METHOD_TYPES__TtP16DriverManagement32DriverKitDaemonAppClientProtocol_
+ __PROTOCOL__TtP16DriverManagement32DriverKitDaemonAppClientProtocol_
+ _flat unique 16DriverManagement0A26KitDaemonAppClientProtocol_p
+ _objc_autorelease
+ _symbolic $s16DriverManagement0A26KitDaemonAppClientProtocolP
+ _symbolic ______p 16DriverManagement0A26KitDaemonAppClientProtocolP
- -[DriverManager refreshForCurrentAppSync]
CStrings:
+ "Connection to service %{public}s invalidated"
+ "Failed to get approval states for current app: %{public}s"
+ "Failed to get scoped approval state"
+ "Unexpected non-third-party entry on scoped app path: %{public}s"
+ "com.apple.DriverKitAppServer"
+ "driverApprovalStatesForCurrentApp(withError:)"
+ "fetchApprovalStatesForCurrentAppSync()"
- "Failed to get approval state"
- "refreshApprovalStatesForCurrentApp()"
- "refreshForCurrentAppSync()"
```
