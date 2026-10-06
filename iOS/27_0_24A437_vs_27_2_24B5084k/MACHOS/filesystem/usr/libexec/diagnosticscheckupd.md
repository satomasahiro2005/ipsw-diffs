## diagnosticscheckupd

> `/usr/libexec/diagnosticscheckupd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4b448` | `0x4cbd8` | **`+0x1790`** |
| `__TEXT.__const` | `0x2088` | `0x2398` | **`+0x310`** |
| `__DATA.__bss` | `0x1c10` | `0x1f10` | **`+0x300`** |
| `__DATA_CONST.__const` | `0x3018` | `0x3318` | **`+0x300`** |
| `__TEXT.__swift5_fieldmd` | `0xe6c` | `0x1018` | **`+0x1ac`** |
| `__TEXT.__swift5_reflstr` | `0x1526` | `0x167d` | **`+0x157`** |
| `__TEXT.__constg_swiftt` | `0x1610` | `0x1740` | **`+0x130`** |
| `__DATA.__objc_const` | `0xe310` | `0xe430` | **`+0x120`** |
| `__TEXT.__objc_methname` | `0x82a1` | `0x83a1` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x380a` | `0x390a` | **`+0x100`** |
| `__DATA.__objc_data` | `0x1bb8` | `0x1c80` | **`+0xc8`** |
| `__TEXT.__swift5_typeref` | `0xc0e` | `0xcaf` | **`+0xa1`** |
| `__TEXT.__objc_stubs` | `0x5b80` | `0x5c20` | **`+0xa0`** |
| `__DATA.__data` | `0x2880` | `0x2910` | **`+0x90`** |
| `__TEXT.__cstring` | `0x2edd` | `0x2f39` | **`+0x5c`** |
| `__TEXT.__objc_methlist` | `0x380c` | `0x3864` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x1378` | `0x13d0` | **`+0x58`** |
| `__TEXT.__objc_classname` | `0xbef` | `0xc27` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0xb84` | `0xbb8` | **`+0x34`** |
| `__DATA.__objc_selrefs` | `0x1df8` | `0x1e28` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x564` | `0x594` | **`+0x30`** |
| `__DATA_CONST.__auth_ptr` | `0x328` | `0x348` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x16e0` | `0x1700` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0xf0` | `0x108` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0xf0` | `0x108` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0xb8` | `0xd0` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x8c` | `0xa0` | **`+0x14`** |
| `__TEXT.__auth_stubs` | `0x15e0` | `0x15d0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0xb00` | `0xaf8` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x668` | `0x660` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x200` | `0x208` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2d4` | `0x2d8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1374.2.2.0.0
+1374.40.35.0.0

-  - /System/Library/PrivateFrameworks/NanoRegistry.framework/NanoRegistry
+  - /System/Library/PrivateFrameworks/PairedDeviceRegistry.framework/PairedDeviceRegistry

+  - /usr/lib/swift/libswiftAccelerate.dylib

+  - /usr/lib/swift/libswiftIntents.dylib

-  Functions: 1864
+  Functions: 1905

-  CStrings:  2396
+  CStrings:  2416
Symbols:
+ _OBJC_CLASS_$_PDRDevice
+ _OBJC_CLASS_$_PDRRegistry
+ _PDRDevicePropertyKeySerialNumber
+ _PDRDidPairNotification
+ _PDRDidUnpairNotification
+ _PDRNotificationKeyDevice
+ __swift_FORCE_LOAD_$_swiftAccelerate
+ __swift_FORCE_LOAD_$_swiftIntents
- _NRDevicePropertyIsPaired
- _NRDevicePropertySerialNumber
- _NRPairedDeviceRegistryDevice
- _NRPairedDeviceRegistryDeviceDidPairNotification
- _NRPairedDeviceRegistryDeviceDidUnpairNotification
- _OBJC_CLASS_$_NRDevice
- _OBJC_CLASS_$_NRPairedDeviceRegistry
- _swift_retain_x8
CStrings:
+ "00000000-0000-0000-0000-000000000000"
+ "T@\"DSHardwareButtonEventMonitor\",&,V_inputBlocker"
+ "[ids] Handled endDevice (normal path); phase now=%ld; no exit scheduled here"
+ "[ids] Handled requestDeviceState; phase=%ld shouldExit=%{bool}d"
+ "[ids] Scheduling exit in 5s; exitReason=%ld"
+ "[ids] appExitRequested; will call xpc_transaction_exit_clean()"
+ "_TtC19diagnosticscheckupd27HomePodStatusDisplayManager"
+ "_createDeviceWithWatchDevice:"
+ "_inputBlocker"
+ "_watchDevicePaired:"
+ "_watchDeviceUnpaired:"
+ "beginInputSuppression"
+ "bluetoothIdentifier"
+ "defaultsBundleIdentifier"
+ "endInputSuppression"
+ "flowTermsAndConditions"
+ "initWithWatchDevice:"
+ "inputBlocker"
+ "isEqualToPDRDevice:"
+ "isPaired"
+ "renderState"
+ "setInputBlocker:"
+ "skipTermsDefaultsKey"
+ "stateLock"
+ "swallowButtonEvent:"
+ "timeoutEnrollment"
- "_createDeviceWithNanoDevice:"
- "_nanoRegistryDevicePaired:"
- "_nanoRegistryDeviceUnpaired:"
- "deviceIDForNRDevice:"
- "initWithNanoDevice:"
- "isEqualToNRDevice:"
```
