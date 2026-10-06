## Sharing

> `/System/Library/PrivateFrameworks/Sharing.framework/Sharing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x385aa0` | `0x38ae6c` | **`+0x53cc`** |
| `__AUTH_CONST.__const` | `0x1a4a8` | `0x1b688` | **`+0x11e0`** |
| `__TEXT.__cstring` | `0x3ab65` | `0x3ad85` | **`+0x220`** |
| `__AUTH_CONST.__cfstring` | `0x13380` | `0x134a0` | **`+0x120`** |
| `__AUTH_CONST.__objc_const` | `0x3c518` | `0x3c608` | **`+0xf0`** |
| `__DATA.__data` | `0xce30` | `0xcf20` | **`+0xf0`** |
| `__TEXT.__objc_methlist` | `0x1509c` | `0x15114` | **`+0x78`** |
| `__AUTH_CONST.__auth_got` | `0x2b28` | `0x2b98` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x9556` | `0x95c2` | **`+0x6c`** |
| `__TEXT.__unwind_info` | `0xedd0` | `0xed68` | **`-0x68`** |
| `__TEXT.__swift5_capture` | `0x3238` | `0x3280` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x9b00` | `0x9b40` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0xbc53` | `0xbc13` | **`-0x40`** |
| `__DATA_CONST.__got` | `0x1390` | `0x13c8` | **`+0x38`** |
| `__AUTH.__data` | `0x3e88` | `0x3eb0` | **`+0x28`** |
| `__DATA.__bss` | `0x3e4f0` | `0x3e510` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x42e2` | `0x4302` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x7900` | `0x7918` | **`+0x18`** |
| `__TEXT.__const` | `0x24c34` | `0x24c44` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x25a0` | `0x25ac` | **`+0xc`** |
| `__TEXT.__swift5_fieldmd` | `0x7870` | `0x787c` | **`+0xc`** |
| `__DATA_CONST.__objc_protolist` | `0x418` | `0x420` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x4360` | `0x4368` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x100dc` | `0x100e4` | **`+0x8`** |

### Other Changes

```diff

-2118.10.4.2.3
+2122.10.2.2.1

-  Functions: 24509
-  Symbols:   20387
-  CStrings:  8841
+  Functions: 24538
+  Symbols:   20417
+  CStrings:  8858
Symbols:
+ +[SFBLEScanner parseNearbyInfoPtr:end:fields:]
+ -[SFBLEDevice buffered]
+ -[SFBLEDevice setBuffered:]
+ -[SFDevice buffered]
+ -[SFDevice setBuffered:]
+ -[SFDeviceSetupSessioniOS walletContentProvider:didRequestPresentationForProxCard:]
+ -[SFDeviceSetupSessioniOS walletContentProviderDidComplete:]
+ _OBJC_IVAR_$_SFBLEDevice._buffered
+ _OBJC_IVAR_$_SFDevice._buffered
+ _OBJC_IVAR_$_SFDeviceSetupSessioniOS._walletContentProvider
+ _PKProximitySetupSourceContentProviderFunction
+ _PassKitUILibrary.sLib
+ _PassKitUILibrary.sOnce
+ _SFSanitizedIdentifier
+ _SFShareSheetActivityTypeAirDrop
+ __OBJC_$_CLASS_METHODS_SFBLEScanner
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_PKProximitySetupSourceContentProviderDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_PKProximitySetupSourceContentProviderDelegate
+ __OBJC_$_PROTOCOL_REFS_PKProximitySetupSourceContentProviderDelegate
+ __OBJC_LABEL_PROTOCOL_$_PKProximitySetupSourceContentProviderDelegate
+ __OBJC_PROTOCOL_$_PKProximitySetupSourceContentProviderDelegate
+ ___PassKitUILibrary_block_invoke
+ ___block_descriptor_40_e8_32bs_e14_v20?0B8B12B16ls32l8
+ ___block_descriptor_40_e8_32s_e14_v20?0B8B12B16ls32l8
+ ___block_descriptor_43_e8_32bs_e5_v8?0ls32l8
+ ___unnamed_68
+ _classPKProximitySetupSourceContentProvider
+ _getPKProximitySetupSourceContentProviderClass
+ _initPKProximitySetupSourceContentProvider
+ _keypath_set.105Tm
+ _os_variant_has_internal_diagnostics
+ _symbolic SDySSSdGz_Xx
+ _symbolic SaySo11NSExtensionCG
+ _symbolic SaySo11NSExtensionCGz_Xx
+ _symbolic So11NSExtensionC
+ _symbolic _____y_____G s11_SetStorageC s8DurationV10FoundationE16UnitsFormatStyleV4UnitV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s8DurationV10FoundationE16UnitsFormatStyleV4UnitV
- -[SFBLEScanner _nearbyParseNearbyInfoPtr:end:fields:]
- _OUTLINED_FUNCTION_63
- ___block_descriptor_40_e8_32bs_e11_v16?0B8B12ls32l8
- ___block_descriptor_40_e8_32s_e11_v16?0B8B12ls32l8
- ___block_descriptor_41_e8_32bs_e5_v8?0ls32l8
- ___unnamed_67
- _keypath_set.101Tm
CStrings:
+ ", Buffered"
+ "-[SFDeviceSetupSessioniOS walletContentProvider:didRequestPresentationForProxCard:]"
+ "-[SFDeviceSetupSessioniOS walletContentProviderDidComplete:]"
+ "/System/Library/PrivateFrameworks/PassKitUI.framework/PassKitUI"
+ "AirDropReadNearbyInfoBuffers"
+ "ExtensionsCache: Extension %s %s activation rule in %s"
+ "LECAHap"
+ "LECAHapLow"
+ "LECATmap"
+ "LECATmapLow"
+ "Mac17,2"
+ "Mac17,6"
+ "Mac17,7"
+ "Mac17,8"
+ "Mac17,9"
+ "Other"
+ "PKProximitySetupSourceContentProvider"
+ "buff"
+ "buffered"
+ "com.apple.UIKit.activity.AirDrop"
+ "com.compuserve.gif"
+ "v20@?0B8B12B16"
+ "walletClientSetup transfer provider did complete\n"
+ "walletClientSetup transfer provider did request presentation: %@\n"
- "ExtensionsCache: Extension %s did not pass activation rule"
- "ExtensionsCache: Extension %s passed activation rule"
- "LECA1"
- "LECA2"
- "LECA3"
- "LECA4"
- "v16@?0B8B12"
```
