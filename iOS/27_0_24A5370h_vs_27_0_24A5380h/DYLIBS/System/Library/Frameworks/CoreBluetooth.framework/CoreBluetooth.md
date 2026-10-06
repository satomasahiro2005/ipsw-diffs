## CoreBluetooth

> `/System/Library/Frameworks/CoreBluetooth.framework/CoreBluetooth`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd7634` | `0xd7a60` | **`+0x42c`** |
| `__AUTH_CONST.__objc_const` | `0x1c470` | `0x1c580` | **`+0x110`** |
| `__TEXT.__cstring` | `0x1adc5` | `0x1ae30` | **`+0x6b`** |
| `__DATA_DIRTY.__objc_data` | `0x1720` | `0x1770` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0xd654` | `0xd6a4` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x11100` | `0x11140` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x5c0` | `0x5e0` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x30f7` | `0x3110` | **`+0x19`** |
| `__DATA_CONST.__objc_selrefs` | `0x5cb0` | `0x5cc8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x29d0` | `0x29e8` | **`+0x18`** |
| `__DATA_DIRTY.__bss` | `0x230` | `0x240` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x136c` | `0x1374` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x350` | `0x358` | **`+0x8`** |
| `__TEXT.__const` | `0x2d01` | `0x2d09` | **`+0x8`** |

### Other Changes

```diff

-2700.41.1.1.0
+2700.43.0.0.0

-  Functions: 5524
-  Symbols:   8412
-  CStrings:  5104
+  Functions: 5532
+  Symbols:   8428
+  CStrings:  5108
Symbols:
+ -[CBDevice companionSetupInfo]
+ -[CBDeviceCompanionSetupInfo .cxx_destruct]
+ -[CBDeviceCompanionSetupInfo action]
+ -[CBDeviceCompanionSetupInfo model]
+ -[CBDeviceCompanionSetupInfo setAction:]
+ -[CBDeviceCompanionSetupInfo setModel:]
+ GCC_except_table527
+ GCC_except_table532
+ GCC_except_table547
+ GCC_except_table610
+ _OBJC_CLASS_$_CBDeviceCompanionSetupInfo
+ _OBJC_IVAR_$_CBDeviceCompanionSetupInfo._action
+ _OBJC_IVAR_$_CBDeviceCompanionSetupInfo._model
+ _OBJC_METACLASS_$_CBDeviceCompanionSetupInfo
+ __OBJC_$_INSTANCE_METHODS_CBDeviceCompanionSetupInfo
+ __OBJC_$_INSTANCE_VARIABLES_CBDeviceCompanionSetupInfo
+ __OBJC_$_PROP_LIST_CBDeviceCompanionSetupInfo
+ __OBJC_CLASS_RO_$_CBDeviceCompanionSetupInfo
+ __OBJC_METACLASS_RO_$_CBDeviceCompanionSetupInfo
+ ___CBDiscoveryLogger_block_invoke
- GCC_except_table521
- GCC_except_table526
- GCC_except_table541
- GCC_except_table604
CStrings:
+ "%@%c"
+ "%u%c%u"
+ "Channel Sounding procedure was terminated by the peer device."
+ "Device found: %{public}@"
+ "FindNearbyLocalFindableAccessoryExtendedRange"
+ "MobileBluetooth-2700.43"
- "%u.%u.%u"
- "MobileBluetooth-2700.41.1.1"
```
