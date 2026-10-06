## ServiceDiscovery

> `/System/Library/PrivateFrameworks/ServiceDiscovery.framework/ServiceDiscovery`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a4448` | `0x1b186c` | **`+0xd424`** |
| `__DATA.__bss` | `0x8f40` | `0xa040` | **`+0x1100`** |
| `__TEXT.__const` | `0xa95c` | `0xb56c` | **`+0xc10`** |
| `__TEXT.__eh_frame` | `0xd04c` | `0xd9e0` | **`+0x994`** |
| `__AUTH_CONST.__const` | `0x59c8` | `0x6000` | **`+0x638`** |
| `__AUTH_CONST.__objc_const` | `0x3488` | `0x3930` | **`+0x4a8`** |
| `__TEXT.__oslogstring` | `0x6c16` | `0x6fa6` | **`+0x390`** |
| `__TEXT.__unwind_info` | `0x4788` | `0x4b08` | **`+0x380`** |
| `__TEXT.__constg_swiftt` | `0x2440` | `0x27a4` | **`+0x364`** |
| `__TEXT.__swift5_typeref` | `0x335b` | `0x361b` | **`+0x2c0`** |
| `__TEXT.__swift5_fieldmd` | `0x1f44` | `0x21c0` | **`+0x27c`** |
| `__DATA.__data` | `0x1918` | `0x1b80` | **`+0x268`** |
| `__TEXT.__swift5_reflstr` | `0x1949` | `0x1b59` | **`+0x210`** |
| `__AUTH.__data` | `0x308` | `0x4e0` | **`+0x1d8`** |
| `__AUTH.__objc_data` | `0x730` | `0x868` | **`+0x138`** |
| `__TEXT.__swift5_capture` | `0x134c` | `0x1424` | **`+0xd8`** |
| `__TEXT.__objc_methlist` | `0xd24` | `0xdcc` | **`+0xa8`** |
| `__TEXT.__swift_as_cont` | `0xab0` | `0xb58` | **`+0xa8`** |
| `__TEXT.__swift5_proto` | `0x6ac` | `0x74c` | **`+0xa0`** |
| `__TEXT.__swift5_assocty` | `0x330` | `0x3c0` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x930` | `0x9a0` | **`+0x70`** |
| `__TEXT.__cstring` | `0x2ad5` | `0x2b45` | **`+0x70`** |
| `__DATA_DIRTY.__data` | `0x3178` | `0x31d8` | **`+0x60`** |
| `__TEXT.__swift_as_entry` | `0x524` | `0x580` | **`+0x5c`** |
| `__AUTH_CONST.__auth_got` | `0x15e0` | `0x1638` | **`+0x58`** |
| `__TEXT.__swift_as_ret` | `0x5ac` | `0x604` | **`+0x58`** |
| `__TEXT.__swift5_types` | `0x21c` | `0x240` | **`+0x24`** |
| `__DATA_CONST.__objc_classlist` | `0x148` | `0x160` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0xb4` | `0xc8` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x6f8` | `0x708` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `0x40` | `0x4c` | **`+0xc`** |

### Other Changes

```diff

-751.200.31.0.0
+751.200.41.0.0

+  - /usr/lib/libMobileGestalt.dylib

-  Functions: 4954
-  Symbols:   1760
-  CStrings:  882
+  Functions: 5223
+  Symbols:   1841
+  CStrings:  906
Symbols:
+ _CUAltDSIDPrimary
+ _GestaltGetDeviceClass
+ _MobileGestalt_get_current_device
+ _MobileGestalt_get_isVirtualDevice
+ _OBJC_CLASS_$_SDPersonalDeviceInfo
+ _OBJC_METACLASS_$_SDPersonalDeviceInfo
+ _OBJC_METACLASS_$__TtC16ServiceDiscoveryP33_8EDB73F28F5D4048504B288E7F9A41EE11KVOObserver
+ __DATA_SDPersonalDeviceInfo
+ __DATA__TtC16ServiceDiscovery19PersonalInfoMonitor
+ __DATA__TtC16ServiceDiscoveryP33_8EDB73F28F5D4048504B288E7F9A41EE11KVOObserver
+ __INSTANCE_METHODS_SDPersonalDeviceInfo
+ __INSTANCE_METHODS__TtC16ServiceDiscoveryP33_8EDB73F28F5D4048504B288E7F9A41EE11KVOObserver
+ __IVARS_SDPersonalDeviceInfo
+ __IVARS__TtC16ServiceDiscovery14SettingMonitor
+ __IVARS__TtC16ServiceDiscovery19PersonalInfoMonitor
+ __IVARS__TtC16ServiceDiscoveryP33_8EDB73F28F5D4048504B288E7F9A41EE11KVOObserver
+ __METACLASS_DATA_SDPersonalDeviceInfo
+ __METACLASS_DATA__TtC16ServiceDiscovery19PersonalInfoMonitor
+ __METACLASS_DATA__TtC16ServiceDiscoveryP33_8EDB73F28F5D4048504B288E7F9A41EE11KVOObserver
+ __PROPERTIES_SDPersonalDeviceInfo
+ ___swift_closure_destructor.25Tm
+ ___swift_memcpy144_8
+ ___swift_memcpy96_8
+ _associated conformance 16ServiceDiscovery18PersonalDeviceInfoV10CodingKeys33_51B2FFC991C640AC7F2F65FFBF9355FALLOSHAASQ
+ _associated conformance 16ServiceDiscovery18PersonalDeviceInfoV10CodingKeys33_51B2FFC991C640AC7F2F65FFBF9355FALLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 16ServiceDiscovery18PersonalDeviceInfoV10CodingKeys33_51B2FFC991C640AC7F2F65FFBF9355FALLOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 16ServiceDiscovery18PersonalDeviceInfoVSHAASQ
+ _associated conformance 16ServiceDiscovery25PersonalDeviceInfoStorageV10CodingKeys33_51B2FFC991C640AC7F2F65FFBF9355FALLOSHAASQ
+ _associated conformance 16ServiceDiscovery25PersonalDeviceInfoStorageV10CodingKeys33_51B2FFC991C640AC7F2F65FFBF9355FALLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 16ServiceDiscovery25PersonalDeviceInfoStorageV10CodingKeys33_51B2FFC991C640AC7F2F65FFBF9355FALLOs0G3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 16ServiceDiscovery25PersonalDeviceInfoStorageV14AttributeFlagsVSHAASQ
+ _associated conformance 16ServiceDiscovery25PersonalDeviceInfoStorageV14AttributeFlagsVs10SetAlgebraAASQ
+ _associated conformance 16ServiceDiscovery25PersonalDeviceInfoStorageV14AttributeFlagsVs10SetAlgebraAAs25ExpressibleByArrayLiteral
+ _associated conformance 16ServiceDiscovery25PersonalDeviceInfoStorageV14AttributeFlagsVs9OptionSetAASY
+ _associated conformance 16ServiceDiscovery25PersonalDeviceInfoStorageV14AttributeFlagsVs9OptionSetAAs0J7Algebra
+ _associated conformance 16ServiceDiscovery25PersonalDeviceInfoStorageVSHAASQ
+ _associated conformance So19NSKeyValueChangeKeyaSHSCSQ
+ _associated conformance So19NSKeyValueChangeKeyas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So19NSKeyValueChangeKeyas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _get_enum_tag_for_layout_string 16ServiceDiscovery25PersonalDeviceInfoStorageVSg
+ _symbolic $s16ServiceDiscovery10RedactableP
+ _symbolic $s16ServiceDiscovery16FetchableSettingP
+ _symbolic $s16ServiceDiscovery27PersonalInfoMonitorDelegateP
+ _symbolic $ss21_ObjectiveCBridgeableP
+ _symbolic SDySS_____G 16ServiceDiscovery19PersonalInfoMonitorC
+ _symbolic SDySS_____G 16ServiceDiscovery25PersonalDeviceInfoStorageV
+ _symbolic SDySi_____G 16ServiceDiscovery25PersonalDeviceInfoStorageV
+ _symbolic SDySi_____GSg 16ServiceDiscovery25PersonalDeviceInfoStorageV
+ _symbolic SbSg
+ _symbolic SbSgSbIeghny_
+ _symbolic So14NSUserDefaultsC
+ _symbolic So14NSUserDefaultsCSg
+ _symbolic So20SDPersonalDeviceInfoCSg
+ _symbolic So8NSStringC
+ _symbolic _____ 16ServiceDiscovery11KVOObserver33_8EDB73F28F5D4048504B288E7F9A41EELLC
+ _symbolic _____ 16ServiceDiscovery14SettingMonitorC
+ _symbolic _____ 16ServiceDiscovery18PersonalDeviceInfoV
+ _symbolic _____ 16ServiceDiscovery18PersonalDeviceInfoV10CodingKeys33_51B2FFC991C640AC7F2F65FFBF9355FALLO
+ _symbolic _____ 16ServiceDiscovery19PersonalInfoMonitorC
+ _symbolic _____ 16ServiceDiscovery25PersonalDeviceInfoStorageV
+ _symbolic _____ 16ServiceDiscovery25PersonalDeviceInfoStorageV10CodingKeys33_51B2FFC991C640AC7F2F65FFBF9355FALLO
+ _symbolic _____ 16ServiceDiscovery25PersonalDeviceInfoStorageV14AttributeFlagsV
+ _symbolic _____ So19NSKeyValueChangeKeya
+ _symbolic _____Sg 16ServiceDiscovery11KVOObserver33_8EDB73F28F5D4048504B288E7F9A41EELLC
+ _symbolic _____Sg 16ServiceDiscovery25PersonalDeviceInfoStorageV
+ _symbolic _____SgXw 16ServiceDiscovery19PersonalInfoMonitorC
+ _symbolic ______p 16ServiceDiscovery27PersonalInfoMonitorDelegateP
+ _symbolic ______pSgXw 16ServiceDiscovery27PersonalInfoMonitorDelegateP
+ _symbolic _____ySS_____G s18_DictionaryStorageC 16ServiceDiscovery018PersonalDeviceInfoB0V
+ _symbolic _____ySS_____G s18_DictionaryStorageC 16ServiceDiscovery19PersonalInfoMonitorC
+ _symbolic _____ySbG 16ServiceDiscovery14SettingMonitorC
+ _symbolic _____ySbGSgXw 16ServiceDiscovery14SettingMonitorC
+ _symbolic _____ySi_____G s18_DictionaryStorageC 16ServiceDiscovery018PersonalDeviceInfoB0V
+ _symbolic _____y_____G s22KeyedDecodingContainerV 16ServiceDiscovery18PersonalDeviceInfoV10CodingKeys33_51B2FFC991C640AC7F2F65FFBF9355FALLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 16ServiceDiscovery25PersonalDeviceInfoStorageV10CodingKeys33_51B2FFC991C640AC7F2F65FFBF9355FALLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 16ServiceDiscovery18PersonalDeviceInfoV10CodingKeys33_51B2FFC991C640AC7F2F65FFBF9355FALLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 16ServiceDiscovery25PersonalDeviceInfoStorageV10CodingKeys33_51B2FFC991C640AC7F2F65FFBF9355FALLO
+ _symbolic xSg
+ _symbolic y_____c 16ServiceDiscovery11KVOObserver33_8EDB73F28F5D4048504B288E7F9A41EELLC
+ _symbolic yxSg_SbtYbcSg
+ _symbolic yyYbc
+ _type_layout_string 16ServiceDiscovery18PersonalDeviceInfoV
+ _type_layout_string 16ServiceDiscovery25PersonalDeviceInfoStorageV
+ _type_layout_string 16ServiceDiscovery25PersonalDeviceInfoStorageV14AttributeFlagsV
+ _type_layout_string So19NSKeyValueChangeKeya
- ___swift_closure_destructor.17Tm
- ___swift_closure_destructor.36Tm
- ___swift_memcpy120_8
- _swift_release_x13
CStrings:
+ "%s Already observing setting"
+ "%s No handler"
+ "%s No observing to stop"
+ "%s Setting changed %s (set: %{bool}d) -> %s (set: %{bool}d)"
+ "%s Setting updated"
+ "%s Settings unavailable"
+ "%s Started observing setting"
+ "%s Stopped observing setting"
+ "Already monitoring PersonalInfo updates for %s"
+ "AltDSID changed from %{sensitive}s to %{sensitive}s"
+ "Delegate is unavailable to receive update"
+ "Ignoring stale PersonalInfo update for %s"
+ "Me Device update: %{bool}d -> %{bool}d (source: %s)"
+ "No change in PersonalInfo for %s: %{sensitive}s"
+ "PersonalInfo: %{sensitive}s"
+ "Primary account changed"
+ "ServiceDiscovery.KVOObserver"
+ "Starting PersonalInfo update monitoring for %s"
+ "Stopping PersonalInfo update monitoring for %s"
+ "System Me Device changed to %{sensitive}s meDeviceIsMe: %s valid: %s"
+ "Updated PersonalInfo for %s [publish %{bool}d]: %{sensitive}s -> %{sensitive}s"
+ "] iCloudAltDSID["
+ "clMeDeviceIsMeOverride"
+ "com.apple.rapport"
```
