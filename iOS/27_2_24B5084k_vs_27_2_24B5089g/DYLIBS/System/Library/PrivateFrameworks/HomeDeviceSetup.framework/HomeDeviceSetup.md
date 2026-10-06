## HomeDeviceSetup

> `/System/Library/PrivateFrameworks/HomeDeviceSetup.framework/HomeDeviceSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x72c3c` | `0x72608` | **`-0x634`** |
| `__TEXT.__cstring` | `0x1aae4` | `0x1a864` | **`-0x280`** |
| `__AUTH_CONST.__objc_const` | `0x78d8` | `0x78a8` | **`-0x30`** |
| `__AUTH_CONST.__cfstring` | `0x55a0` | `0x5580` | **`-0x20`** |
| `__AUTH_CONST.__const` | `0xc38` | `0xc18` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x1980` | `0x1960` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2dd0` | `0x2dc0` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x3484` | `0x3474` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x1870` | `0x1860` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0xa50` | `0xa4c` | **`-0x4`** |

### Other Changes

```diff

-405.10.26.0.0
+405.10.29.0.0

-  Functions: 3080
-  Symbols:   3341
-  CStrings:  3122
+  Functions: 3069
+  Symbols:   3336
+  CStrings:  3113
Symbols:
+ +[HDSDefaults getOptionalBoolForKey:]
+ -[HDSSetupSession _runFinishComplete]
+ -[HDSSetupSession _stereoCounterpartExpectedModelPrefix]
+ GCC_except_table311
+ GCC_except_table374
+ GCC_except_table426
+ ___37-[HDSSetupSession _runFinishComplete]_block_invoke
- -[HDSDeviceOperationHomeKitSetup _idsIdentifiersForAccessories:companionLinkClient:]
- -[HDSDeviceOperationHomeKitSetup companionLinkClient]
- -[HDSDeviceOperationHomeKitSetup modelForStereoPairVersion:]
- -[HDSDeviceOperationHomeKitSetup setCompanionLinkClient:]
- GCC_except_table310
- GCC_except_table372
- GCC_except_table424
- _OBJC_IVAR_$_HDSDeviceOperationHomeKitSetup._companionLinkClient
- ___44-[HDSSetupSession _runFinishResponse:error:]_block_invoke
- ___84-[HDSDeviceOperationHomeKitSetup _idsIdentifiersForAccessories:companionLinkClient:]_block_invoke
- ___84-[HDSDeviceOperationHomeKitSetup _idsIdentifiersForAccessories:companionLinkClient:]_block_invoke_2
- ___block_descriptor_32_e38_B32?0"RPCompanionLinkDevice"8Q16^B24l
CStrings:
+ "-[HDSSetupSession _runFinishComplete]"
+ "-[HDSSetupSession _runFinishComplete]_block_invoke"
+ "Ignoring color from %@ (model %@), setting up model code %d\n"
- "### _idsIdentifiersForAccessories: %@ has no IDS identifier\n"
- "### _idsIdentifiersForAccessories: %@ not found in Rapport\n"
- "### _idsIdentifiersForAccessories: nil accessories or client\n"
- "### _idsIdentifiersForAccessories: no active devices\n"
- "### _idsIdentifiersForAccessories: unregistered device has no IDS identifier\n"
- "-[HDSDeviceOperationHomeKitSetup _idsIdentifiersForAccessories:companionLinkClient:]"
- "-[HDSSetupSession _runFinishResponse:error:]_block_invoke"
- "AudioAccessory6,1"
- "_idsIdentifiersForAccessories: %@ -> IDS: %@ (matched as unregistered device, model: %@)\n"
- "_idsIdentifiersForAccessories: %@ -> IDS: %@ (matched by HomeKit UUID)\n"
- "_idsIdentifiersForAccessories: %@ not found by HomeKit UUID, checking for unregistered device\n"
- "_idsIdentifiersForAccessories: activeDevices count=%lu\n"
```
