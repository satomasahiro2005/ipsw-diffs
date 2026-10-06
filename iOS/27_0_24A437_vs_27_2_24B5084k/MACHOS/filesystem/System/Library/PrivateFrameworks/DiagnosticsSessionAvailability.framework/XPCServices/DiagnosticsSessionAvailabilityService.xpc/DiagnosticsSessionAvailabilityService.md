## DiagnosticsSessionAvailabilityService

> `/System/Library/PrivateFrameworks/DiagnosticsSessionAvailability.framework/XPCServices/DiagnosticsSessionAvailabilityService.xpc/DiagnosticsSessionAvailabilityService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x27c9` | `0x27bd` | **`-0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1374.2.2.0.0
+1374.40.35.0.0

-  - /System/Library/PrivateFrameworks/NanoRegistry.framework/NanoRegistry
+  - /System/Library/PrivateFrameworks/PairedDeviceRegistry.framework/PairedDeviceRegistry
Symbols:
+ _OBJC_CLASS_$_PDRRegistry
+ _PDRDevicePropertyKeySerialNumber
+ _PDRDidPairNotification
+ _PDRDidUnpairNotification
+ _PDRNotificationKeyDevice
- _NRDevicePropertySerialNumber
- _NRPairedDeviceRegistryDevice
- _NRPairedDeviceRegistryDeviceDidPairNotification
- _NRPairedDeviceRegistryDeviceDidUnpairNotification
- _OBJC_CLASS_$_NRPairedDeviceRegistry
CStrings:
+ "_createDeviceWithWatchDevice:"
+ "_watchDevicePaired:"
+ "_watchDeviceUnpaired:"
+ "initWithWatchDevice:"
- "_createDeviceWithNanoDevice:"
- "_nanoRegistryDevicePaired:"
- "_nanoRegistryDeviceUnpaired:"
- "initWithNanoDevice:"
```
