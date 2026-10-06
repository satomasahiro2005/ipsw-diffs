## sharingd

> `/usr/libexec/sharingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6b71fc` | `0x6b7d44` | **`+0xb48`** |
| `__TEXT.__cstring` | `0x3f301` | `0x3f4b1` | **`+0x1b0`** |
| `__TEXT.__objc_methname` | `0x4ee35` | `0x4ef65` | **`+0x130`** |
| `__TEXT.__eh_frame` | `0x258fc` | `0x259bc` | **`+0xc0`** |
| `__DATA_CONST.__cfstring` | `0x198c0` | `0x19960` | **`+0xa0`** |
| `__TEXT.__objc_stubs` | `0x378e0` | `0x37980` | **`+0xa0`** |
| `__TEXT.__auth_stubs` | `0xb180` | `0xb200` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x149e8` | `0x14a58` | **`+0x70`** |
| `__DATA_CONST.__auth_got` | `0x58d0` | `0x5910` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x3d6c3` | `0x3d683` | **`-0x40`** |
| `__DATA.__objc_selrefs` | `0x11168` | `0x111a0` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x1e694` | `0x1e6cc` | **`+0x38`** |
| `__DATA.__data` | `0x14bf8` | `0x14bc8` | **`-0x30`** |
| `__TEXT.__const` | `0x160a8` | `0x160d8` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0xbcc2` | `0xbce2` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x816a` | `0x8186` | **`+0x1c`** |
| `__DATA_CONST.__auth_ptr` | `0x4478` | `0x4490` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x68cc` | `0x68e0` | **`+0x14`** |
| `__DATA_CONST.__const` | `0x1ce28` | `0x1ce18` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x3b68` | `0x3b78` | **`+0x10`** |
| `__DATA.__objc_data` | `0xa200` | `0xa208` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x79b8` | `0x79c0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2131.20.71.0.0
+2131.21.21.0.0

-  Functions: 26468
-  Symbols:   5076
-  CStrings:  27635
+  Functions: 26483
+  Symbols:   5086
+  CStrings:  27657
Symbols:
+ _$s10Foundation3URLV7SharingE9hasScheme2inSbShyAD9URLSchemeVG_tF
+ _$s10Foundation4DateV2leoiySbAC_ACtFZ
+ _$s7Sharing9URLSchemeV4httpACvgZ
+ _$s7Sharing9URLSchemeV5httpsACvgZ
+ _$s7Sharing9URLSchemeVMa
+ _$s7Sharing9URLSchemeVMn
+ _$s7Sharing9URLSchemeVSHAAMc
+ _$s7Sharing9URLSchemeVSQAAMc
+ _MKBUnlockDeviceWithACM
+ _SDAKSDataIsExternalACMContext
+ _dispatch_get_specific
- _SDAutoUnlockManagerMetricWiFiResultsKey
CStrings:
+ "### Ignoring received object from unpaired peer %@\n"
+ "-[SDProximityPairingAgent _testB389UIWithParams:]"
+ "-[SDRemoteInteractionAgent _serverEnsureStarted]_block_invoke"
+ "DiagnosticMock"
+ "DiagnosticMockStart"
+ "Filtering out endpoint %s - contactID %s not found in %s"
+ "Invalid parameters (passcode ref = %@)"
+ "MusicHandoffScan"
+ "PIN Auto-Accept invocation rejected: not available on customer builds"
+ "Starting DADaemonSession to monitor paired notification devices"
+ "Stopping DADaemonSession"
+ "T@\"NSData\",C,N,V_passcodeRef"
+ "TestContinuityKeyboardBegin"
+ "Testing AirTag pairing UI (pid=0x%x, color=%u)\n"
+ "TriggerProximityAutoFillDetected"
+ "_isAirTagTestParams:"
+ "_passcodeRef"
+ "_testB389UIWithParams:"
+ "b389"
+ "battery=%hhu"
+ "color=%u"
+ "createPairingLockSessionWithDevice:passcodeRef:"
+ "deviceStatus or paired contact storage"
+ "enableAutoUnlockWithDevice:passcodeRef:"
+ "enableAutoUnlockWithDevice:passcodeRef:clientProxy:"
+ "idsDevices"
+ "multi"
+ "onqueue_idsDevices"
+ "passcodeRef"
+ "setPasscodeRef:"
+ "testAdvertisingFound:model:colorCode:batteryPayload:multi:engravingData:"
+ "v40@0:8@\"SFAutoUnlockDevice\"16@\"NSData\"24@\"<SFUnlockClientProtocol>\"32"
+ "v48@0:8I16@20I28C32B36@40"
+ "validatePasscodeRef:"
- "Ad-hoc paired endpoint %s has paired contact %s"
- "Filtering out ad-hoc paired endpoint %s - contactID %s not found in paired contact storage"
- "Filtering out endpoint %s - contactID %s not found in deviceStatus"
- "Invalid parameters (passcode = %@)"
- "Starting DASession to monitor paired notification devices"
- "Stopping DASession"
- "T@\"NSString\",C,N,V_passcode"
- "createPairingLockSessionWithDevice:passcode:"
- "enableAutoUnlockWithDevice:passcode:"
- "enableAutoUnlockWithDevice:passcode:clientProxy:"
- "v40@0:8@\"SFAutoUnlockDevice\"16@\"NSString\"24@\"<SFUnlockClientProtocol>\"32"
- "validatePasscode:"
```
