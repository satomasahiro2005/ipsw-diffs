## BacklightServices

> `/System/Library/PrivateFrameworks/BacklightServices.framework/BacklightServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a070` | `0x2a808` | **`+0x798`** |
| `__AUTH_CONST.__objc_const` | `0x8290` | `0x8488` | **`+0x1f8`** |
| `__TEXT.__objc_methlist` | `0x38f4` | `0x39cc` | **`+0xd8`** |
| `__AUTH.__objc_data` | `0x1720` | `0x17c0` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x2420` | `0x2480` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x16b8` | `0x16f0` | **`+0x38`** |
| `__TEXT.__cstring` | `0x1bc7` | `0x1b91` | **`-0x36`** |
| `__TEXT.__unwind_info` | `0x1090` | `0x10b0` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x2e4` | `0x2f4` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x360` | `0x370` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x1c0` | `0x1d0` | **`+0x10`** |
| `__DATA.__bss` | `0xe1` | `0xd9` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x408` | `0x410` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0xb0` | `0xb8` | **`+0x8`** |

### Other Changes

```diff

-6.1.3.0.0
+6.1.4.0.0

-  Functions: 1352
-  Symbols:   2752
-  CStrings:  531
+  Functions: 1368
+  Symbols:   2789
+  CStrings:  533
Symbols:
+ +[BLSBacklightProxyObservation observationForObserver:backlight:]
+ +[BLSPendingBacklightProxy addObservation:toBacklightProxy:]
+ -[BLSBacklightProxyObservation .cxx_destruct]
+ -[BLSBacklightProxyObservation backlightForProxy:]
+ -[BLSBacklightProxyObservation backlight]
+ -[BLSBacklightProxyObservation description]
+ -[BLSBacklightProxyObservation initWithObserver:backlight:]
+ -[BLSBacklightProxyObservation observer]
+ -[BLSPendingBacklightProxy _addObserver:forBacklight:]
+ -[BLSPendingBacklightProxy addObserver:forBacklight:]
+ -[BLSPendingBacklightProxy initForDisplay:]
+ -[BLSXPCBacklightProxy _addObserver:forBacklight:]
+ -[BLSXPCBacklightProxy addObserver:forBacklight:]
+ -[BLSXPCBacklightProxy lock_allDidChangeAlwaysOnEnabledObservations]
+ -[BLSXPCBacklightProxy lock_allDidCompleteUpdateToStateObservations]
+ -[BLSXPCBacklightProxy lock_allObservationsPassingTest:]
+ -[BLSXPCBacklightProxy lock_enumerateObservationsWithBlock:]
+ -[BLSXPCBacklightProxyObservation .cxx_destruct]
+ -[BLSXPCBacklightProxyObservation description]
+ -[BLSXPCBacklightProxyObservation initWithObserver:backlight:]
+ -[BLSXPCBacklightProxyObservation mask]
+ _OBJC_CLASS_$_BLSBacklightProxyObservation
+ _OBJC_CLASS_$_BLSXPCBacklightProxyObservation
+ _OBJC_IVAR_$_BLSBacklightProxyObservation._backlight
+ _OBJC_IVAR_$_BLSBacklightProxyObservation._observer
+ _OBJC_IVAR_$_BLSPendingBacklightProxy._display
+ _OBJC_IVAR_$_BLSPendingBacklightProxy._observations
+ _OBJC_IVAR_$_BLSXPCBacklightProxyObservation._mask
+ _OBJC_METACLASS_$_BLSBacklightProxyObservation
+ _OBJC_METACLASS_$_BLSXPCBacklightProxyObservation
+ __OBJC_$_CLASS_METHODS_BLSBacklightProxyObservation
+ __OBJC_$_INSTANCE_METHODS_BLSBacklightProxyObservation
+ __OBJC_$_INSTANCE_METHODS_BLSXPCBacklightProxyObservation
+ __OBJC_$_INSTANCE_VARIABLES_BLSBacklightProxyObservation
+ __OBJC_$_INSTANCE_VARIABLES_BLSXPCBacklightProxyObservation
+ __OBJC_$_PROP_LIST_BLSBacklightProxyObservation
+ __OBJC_$_PROP_LIST_BLSXPCBacklightProxyObservation
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_BLSBacklightProxy
+ __OBJC_$_PROTOCOL_METHOD_TYPES_BLSBacklightProxy
+ __OBJC_CLASS_RO_$_BLSBacklightProxyObservation
+ __OBJC_CLASS_RO_$_BLSXPCBacklightProxyObservation
+ __OBJC_METACLASS_RO_$_BLSBacklightProxyObservation
+ __OBJC_METACLASS_RO_$_BLSXPCBacklightProxyObservation
+ ___56-[BLSXPCBacklightProxy lock_allObservationsPassingTest:]_block_invoke
+ ___68-[BLSXPCBacklightProxy lock_allDidChangeAlwaysOnEnabledObservations]_block_invoke
+ ___68-[BLSXPCBacklightProxy lock_allDidCompleteUpdateToStateObservations]_block_invoke
+ ___block_descriptor_32_e41_B16?0"BLSXPCBacklightProxyObservation"8l
+ ___block_descriptor_48_e8_32s40bs_e41_v16?0"BLSXPCBacklightProxyObservation"8ls40l8s32l8
+ ___block_descriptor_58_e8_32s40s48s_e41_v16?0"BLSXPCBacklightProxyObservation"8ls32l8s40l8s48l8
- -[BLSPendingBacklightProxy init]
- -[BLSXPCBacklightProxy lock_allDidChangeAlwaysOnEnabledObservers]
- -[BLSXPCBacklightProxy lock_allDidCompleteUpdateToStateObservers]
- -[BLSXPCBacklightProxy lock_allObserversPassingTest:]
- -[BLSXPCBacklightProxy lock_enumerateObserversWithBlock:]
- _OBJC_IVAR_$_BLSPendingBacklightProxy._observers
- ___53-[BLSXPCBacklightProxy lock_allObserversPassingTest:]_block_invoke
- ___65-[BLSXPCBacklightProxy lock_allDidChangeAlwaysOnEnabledObservers]_block_invoke
- ___65-[BLSXPCBacklightProxy lock_allDidCompleteUpdateToStateObservers]_block_invoke
- ___block_descriptor_32_e75_B24?0"<BLSBacklightStateObserving>"8"BLSXPCBacklightProxyObserverMask"16l
- ___block_descriptor_48_e8_32s40bs_e75_v24?0"<BLSBacklightStateObserving>"8"BLSXPCBacklightProxyObserverMask"16ls40l8s32l8
- ___block_descriptor_58_e8_32s40s48s_e75_v24?0"<BLSBacklightStateObserving>"8"BLSXPCBacklightProxyObserverMask"16ls32l8s40l8s48l8
CStrings:
+ "B16@?0@\"BLSXPCBacklightProxyObservation\"8"
+ "mask"
+ "observer"
+ "v16@?0@\"BLSXPCBacklightProxyObservation\"8"
- "B24@?0@\"<BLSBacklightStateObserving>\"8@\"BLSXPCBacklightProxyObserverMask\"16"
- "v24@?0@\"<BLSBacklightStateObserving>\"8@\"BLSXPCBacklightProxyObserverMask\"16"
```
