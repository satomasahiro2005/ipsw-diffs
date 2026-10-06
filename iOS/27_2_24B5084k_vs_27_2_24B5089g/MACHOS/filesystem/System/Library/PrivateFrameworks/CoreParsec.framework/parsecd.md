## parsecd

> `/System/Library/PrivateFrameworks/CoreParsec.framework/parsecd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17af6c` | `0x17f028` | **`+0x40bc`** |
| `__DATA_CONST.__const` | `0x10790` | `0x109d0` | **`+0x240`** |
| `__TEXT.__const` | `0xf150` | `0xf360` | **`+0x210`** |
| `__DATA.__data` | `0x9ca0` | `0x9e90` | **`+0x1f0`** |
| `__TEXT.__eh_frame` | `0x7820` | `0x79c0` | **`+0x1a0`** |
| `__TEXT.__swift5_typeref` | `0x53ba` | `0x5554` | **`+0x19a`** |
| `__TEXT.__constg_swiftt` | `0x5a28` | `0x5b24` | **`+0xfc`** |
| `__DATA.__objc_const` | `0x74f8` | `0x75f0` | **`+0xf8`** |
| `__TEXT.__unwind_info` | `0x5578` | `0x5668` | **`+0xf0`** |
| `__TEXT.__swift5_fieldmd` | `0x5200` | `0x52b4` | **`+0xb4`** |
| `__TEXT.__auth_stubs` | `0x51f0` | `0x5290` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x6266` | `0x6306` | **`+0xa0`** |
| `__DATA.__bss` | `0xda00` | `0xda80` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x6655` | `0x66c5` | **`+0x70`** |
| `__TEXT.__swift5_capture` | `0x3afc` | `0x3b6c` | **`+0x70`** |
| `__TEXT.__objc_stubs` | `0x41e0` | `0x4240` | **`+0x60`** |
| `__DATA_CONST.__auth_got` | `0x2908` | `0x2958` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x14a0` | `0x14f0` | **`+0x50`** |
| `__TEXT.__cstring` | `0x69d4` | `0x6a24` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x55e3` | `0x5633` | **`+0x50`** |
| `__DATA_CONST.__auth_ptr` | `0x1f20` | `0x1f60` | **`+0x40`** |
| `__TEXT.__objc_classname` | `0x13d7` | `0x1407` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0x118` | `0x13c` | **`+0x24`** |
| `__DATA.__objc_selrefs` | `0x1590` | `0x15a8` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0xa4` | `0xb8` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0x8f4` | `0x904` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `0x138` | `0x144` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x494` | `0x4a0` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0xbc` | `0xc8` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x2e0` | `0x2e8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-3605.21.1.1.1
+3605.23.1.1.1

+  - /System/Library/PrivateFrameworks/NanoRegistry.framework/NanoRegistry

-  Functions: 9125
-  Symbols:   2380
-  CStrings:  2553
+  Functions: 9219
+  Symbols:   2401
+  CStrings:  2564
Symbols:
+ _$s10PegasusAPI020Apple_Parsec_Search_A12QueryContextV15companionDeviceSayAA021Useragentpb_CompanionI0VGvs
+ _$s10PegasusAPI21Useragentpb_UserAgentV14buildOsVersionSSvs
+ _$s10PegasusAPI21Useragentpb_UserAgentV14productVersionSSvs
+ _$s10PegasusAPI26Useragentpb_DeviceMetadataV010regulatoryD5ModelSSvs
+ _$s10PegasusAPI27Useragentpb_CompanionDeviceV14deviceMetadataAA0c1_eG0VvM
+ _$s10PegasusAPI27Useragentpb_CompanionDeviceV18companionUserAgentAA0c1_gH0VvM
+ _$s10PegasusAPI27Useragentpb_CompanionDeviceVACycfC
+ _$s10PegasusAPI27Useragentpb_CompanionDeviceVMa
+ _$s10PegasusAPI27Useragentpb_CompanionDeviceVMn
+ _$sScS12ContinuationV13onTerminationyAB0C0Oyx__GYbcSgvs
+ _$sScSMa
+ _$sSo17OS_dispatch_queueC8DispatchE20AutoreleaseFrequencyO7inherityA2EmFWC
+ _NRDevicePropertyRegulatoryModelNumber
+ _NRDevicePropertySystemBuildVersion
+ _NRDevicePropertySystemVersion
+ _NRPairedDeviceRegistryDeviceDidPairDarwinNotification
+ _NRPairedDeviceRegistryDeviceDidUnpairDarwinNotification
+ _NRPairedDeviceRegistryPairedDeviceDidChangeVersionDarwinNotification
+ _NRPairedDeviceRegistryWatchDidBecomeActiveDarwinNotification
+ _NRRestartedDarwinNotification
+ _OBJC_CLASS_$_NRPairedDeviceRegistry
CStrings:
+ "Active paired device is missing a required property"
+ "Failed to observe %s: %u"
+ "Re-reading the paired accessory after %{public}s"
+ "_TtC7parsecd23CompanionDeviceProvider"
+ "activePairedDevice()"
+ "com.apple.parsecd.paired-device-read"
+ "companionDeviceProvider"
+ "getActivePairedDeviceExcludingAltAccount"
+ "readLoop"
+ "sharedInstance"
+ "valueForProperty:"
```
