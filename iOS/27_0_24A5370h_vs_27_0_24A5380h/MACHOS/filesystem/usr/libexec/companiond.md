## companiond

> `/usr/libexec/companiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x894b4` | `0x8bffc` | **`+0x2b48`** |
| `__TEXT.__eh_frame` | `0x4cb0` | `0x4ed0` | **`+0x220`** |
| `__DATA.__objc_data` | `0x1a30` | `0x18e0` | **`-0x150`** |
| `__TEXT.__objc_stubs` | `0x4260` | `0x43a0` | **`+0x140`** |
| `__TEXT.__oslogstring` | `0x404b` | `0x417e` | **`+0x133`** |
| `__DATA.__objc_const` | `0x7640` | `0x7548` | **`-0xf8`** |
| `__TEXT.__constg_swiftt` | `0x8b8` | `0x7ec` | **`-0xcc`** |
| `__DATA_CONST.__const` | `0x25d0` | `0x2560` | **`-0x70`** |
| `__TEXT.__swift5_reflstr` | `0x894` | `0x832` | **`-0x62`** |
| `__TEXT.__objc_methname` | `0x60b5` | `0x6115` | **`+0x60`** |
| `__DATA.__data` | `0x1e70` | `0x1e20` | **`-0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x86c` | `0x820` | **`-0x4c`** |
| `__TEXT.__objc_methlist` | `0x2ba8` | `0x2b60` | **`-0x48`** |
| `__TEXT.__cstring` | `0x2625` | `0x2669` | **`+0x44`** |
| `__DATA.__objc_selrefs` | `0x14f0` | `0x1530` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x2520` | `0x2558` | **`+0x38`** |
| `__TEXT.__swift5_capture` | `0x784` | `0x754` | **`-0x30`** |
| `__TEXT.__objc_methtype` | `0x15b7` | `0x1588` | **`-0x2f`** |
| `__TEXT.__gcc_except_tab` | `0x1a84` | `0x1ab0` | **`+0x2c`** |
| `__TEXT.__auth_stubs` | `0x2d60` | `0x2d80` | **`+0x20`** |
| `__TEXT.__const` | `0x20b6` | `0x2096` | **`-0x20`** |
| `__TEXT.__objc_classname` | `0xb67` | `0xb48` | **`-0x1f`** |
| `__TEXT.__swift5_typeref` | `0xc86` | `0xc9f` | **`+0x19`** |
| `__TEXT.__swift_as_cont` | `0x390` | `0x3a8` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x3c` | `0x28` | **`-0x14`** |
| `__DATA_CONST.__auth_got` | `0x16c0` | `0x16d0` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x1c0` | `0x1d0` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x560` | `0x558` | **`-0x8`** |
| `__DATA_CONST.__got` | `0xd10` | `0xd08` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x248` | `0x240` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x8c` | `0x84` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x1a8` | `0x1b0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x40c` | `0x410` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-524.0.16.0.0
+524.0.26.0.0

-  Functions: 2312
-  Symbols:   1273
-  CStrings:  1943
+  Functions: 2295
+  Symbols:   1274
+  CStrings:  1952
Symbols:
+ _$s17CompanionServices32CPSRequesterUseCaseConfigurationV18requiresSharedHomeSbvg
+ _$s17CompanionServices32CPSRequesterUseCaseConfigurationV19requiresSameAccountSbvg
+ _$s17CompanionServices32CPSRequesterUseCaseConfigurationV6TargetO9accountIDSSSgvg
+ _$s17CompanionServices32CPSRequesterUseCaseConfigurationV7targetsSayAC6TargetOGSgvs
- _$sSo17OS_dispatch_queueC8DispatchE4mainABvgZ
- _OBJC_CLASS_$_OS_dispatch_queue
- _swift_bridgeObjectRetain_n
CStrings:
+ "@\"CBDiscovery\""
+ "Bluetooth scanner older setup device lost: %@"
+ "Bluetooth scanner setup device found: %@"
+ "Bluetooth scanner setup device lost. Invalidating."
+ "Bluetooth scanner start failed: %@"
+ "No account store"
+ "No primary account"
+ "No setup ID in advertisement. Not starting Bluetooth scanner."
+ "Starting Bluetooth scanner. setupID=0x%04x"
+ "[%s] bluetooth scanner device found: ignored, not sharedHome, %@"
+ "_bluetoothScannerFoundDevice:"
+ "_bluetoothScannerLostDevice:"
+ "_setupID"
+ "_setupIDForDevice:"
+ "_startBluetoothScanner"
+ "_stopBluetoothScanner"
+ "aa_primaryAppleAccountWithCompletion:"
+ "addDiscoveryType:"
+ "discoveredDevices"
+ "nearbyActionExtraData"
+ "numberWithUnsignedShort:"
+ "setUseCase:"
+ "unsignedShortValue"
+ "v24@?0@\"ACAccount\"8@\"NSError\"16"
- "@\"OS_dispatch_queue\""
- "@\"_TtC10companiond11CDCSKClient\""
- "@28@0:8@16i24"
- "Setup not needed handler called. Invalidating."
- "T@\"OS_dispatch_queue\",N,&,VdispatchQueue"
- "T@?,N,C"
- "_TtC10companiond11CDCSKClient"
- "_cskClient"
- "_startCSKClient"
- "bluetoothDevice"
- "companiond.CDCSKClient"
- "initWithBluetoothDevice:discoveryType:"
- "invalidateDone"
- "setSetupNotNeededHandler:"
- "setupNotNeededHandler"
```
