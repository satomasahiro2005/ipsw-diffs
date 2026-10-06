## ReplicatorDependencies

> `/System/Library/PrivateFrameworks/ReplicatorDependencies.framework/ReplicatorDependencies`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0x1910` | `0x1610` | **`-0x300`** |
| `__TEXT.__text` | `0x29a94` | `0x29c5c` | **`+0x1c8`** |
| `__TEXT.__const` | `0x1e94` | `0x1ce4` | **`-0x1b0`** |
| `__TEXT.__cstring` | `0x511` | `0x5e1` | **`+0xd0`** |
| `__AUTH_CONST.__const` | `0x2120` | `0x21e8` | **`+0xc8`** |
| `__TEXT.__swift5_reflstr` | `0x838` | `0x898` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x47c` | `0x4cc` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0xc00` | `0xbb8` | **`-0x48`** |
| `__AUTH_CONST.__objc_const` | `0x1288` | `0x12c8` | **`+0x40`** |
| `__DATA_DIRTY.__objc_data` | `0x320` | `0x360` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x11a1` | `0x11e1` | **`+0x40`** |
| `__TEXT.__swift5_assocty` | `0x1b0` | `0x180` | **`-0x30`** |
| `__AUTH_CONST.__auth_got` | `0xbc8` | `0xba0` | **`-0x28`** |
| `__TEXT.__swift5_proto` | `0x148` | `0x130` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0xb58` | `0xb40` | **`-0x18`** |
| `__TEXT.__swift5_builtin` | `0x50` | `0x3c` | **`-0x14`** |
| `__DATA.__data` | `0x540` | `0x530` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2c0` | `0x2b0` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xa6c` | `0xa5c` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x31c` | `0x314` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0x1118` | `0x111c` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0xb0` | `0xac` | **`-0x4`** |

### Other Changes

```diff

-173.0.0.0.0
+176.0.0.0.0

-  - /System/Library/PrivateFrameworks/NanoRegistry.framework/NanoRegistry
+  - /System/Library/PrivateFrameworks/PairedDeviceRegistry.framework/PairedDeviceRegistry

-  Functions: 1190
-  Symbols:   618
-  CStrings:  114
+  Functions: 1188
+  Symbols:   604
+  CStrings:  119
Symbols:
+ _OBJC_CLASS_$_PDRRegistry
+ __INSTANCE_METHODS__TtC22ReplicatorDependencies22IDSPairedDeviceMonitor
- _NRPairedDeviceRegistryDeviceDidBecomeActive
- _NRPairedDeviceRegistryDeviceDidBecomeInactive
- _NRPairedDeviceRegistryDeviceDidPairNotification
- _NRPairedDeviceRegistryDeviceDidUnpairNotification
- _NRPairedDeviceRegistryPairedDeviceDidChangeVersionDarwinNotification
- _NRPairedDeviceRegistryWatchDidBecomeActiveDarwinNotification
- _OBJC_CLASS_$_NRPairedDeviceRegistry
- __OBJC_$_INSTANCE_METHODS__TtC22ReplicatorDependencies22IDSPairedDeviceMonitor(ReplicatorDependencies)
- _associated conformance So18NSNotificationNameaSHSCSQ
- _associated conformance So18NSNotificationNameas20_SwiftNewtypeWrapperSCSY
- _associated conformance So18NSNotificationNameas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
- _objc_retain_x27
- _symbolic $ss21_ObjectiveCBridgeableP
- _symbolic So8NSStringC
- _symbolic _____ So18NSNotificationNamea
- _type_layout_string So18NSNotificationNamea
CStrings:
+ "Watch paired, will check for pairing change"
+ "Watch unpaired, will check for pairing change"
+ "com.apple.nanoregistry.devicedidpair"
+ "com.apple.nanoregistry.devicedidunpair"
+ "com.apple.nanoregistry.paireddevicedidchangeversion"
+ "com.apple.nanoregistry.watchdidbecomeactive"
- "No NanoRegistry singleton"
```
