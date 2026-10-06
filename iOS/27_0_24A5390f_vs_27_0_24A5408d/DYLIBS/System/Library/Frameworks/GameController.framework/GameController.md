## GameController

> `/System/Library/Frameworks/GameController.framework/GameController`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x100990` | `0x10569c` | **`+0x4d0c`** |
| `__AUTH_CONST.__objc_const` | `0x4cbb8` | `0x4d818` | **`+0xc60`** |
| `__TEXT.__objc_methlist` | `0xff54` | `0x10124` | **`+0x1d0`** |
| `__AUTH.__objc_data` | `0x5198` | `0x52d8` | **`+0x140`** |
| `__AUTH_CONST.__cfstring` | `0xb380` | `0xb4c0` | **`+0x140`** |
| `__DATA_CONST.__const` | `0x2c70` | `0x2d40` | **`+0xd0`** |
| `__TEXT.__gcc_except_tab` | `0x37d0` | `0x3894` | **`+0xc4`** |
| `__TEXT.__unwind_info` | `0x4de0` | `0x4e98` | **`+0xb8`** |
| `__TEXT.__cstring` | `0xa101` | `0xa191` | **`+0x90`** |
| `__AUTH_CONST.__objc_intobj` | `0x1098` | `0x10c8` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x16a0` | `0x16c0` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0xa28` | `0xa48` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x4f68` | `0x4f88` | **`+0x20`** |
| `__DATA_CONST.__objc_superrefs` | `0x900` | `0x918` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xdf0` | `0xe00` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x200` | `0x210` | **`+0x10`** |

### Other Changes

```diff

-14.0.21.0.0
+14.0.24.0.0

-  Functions: 7692
-  Symbols:   14892
-  CStrings:  2427
+  Functions: 7731
+  Symbols:   14986
+  CStrings:  2437
Symbols:
+ +[_GCCollectionEventGamepadEventAdapterConfig supportsSecureCoding]
+ +[_GCCollectionEventGamepadEventAdapterDescription supportsSecureCoding]
+ +[_GCSteam2ControllerProfile deviceManager:prepareLogicalDevice:]
+ +[_GCSteam2ControllerProfile deviceManager:willPublishPhysicalDevice:]
+ +[_GCSteam2ControllerProfile deviceManager]
+ +[_GCSteam2ControllerProfile logicalDevice:getSystemButtonName:sfSymbolName:needsMFiCompatibility:]
+ +[_GCSteam2ControllerProfile logicalDevice:makeControllerInputDescriptionWithIdentifier:bindings:]
+ +[_GCSteam2ControllerProfile logicalDevice:makeControllerPhysicalInputProfileDescriptionWithIdentifier:bindings:]
+ +[_GCSteam2ControllerProfile logicalDeviceControllerProductCategory:]
+ +[_GCSteam2ControllerProfile physicalDeviceGetHapticCapabilities:]
+ +[_GCSteam2ControllerProfile physicalDeviceGetHapticCapabilityGraph:]
+ -[_GCCollectionEventGamepadEventAdapter .cxx_destruct]
+ -[_GCCollectionEventGamepadEventAdapter dealloc]
+ -[_GCCollectionEventGamepadEventAdapter initWithConfiguration:source:]
+ -[_GCCollectionEventGamepadEventAdapter init]
+ -[_GCCollectionEventGamepadEventAdapter observeGamepadEvents:]
+ -[_GCCollectionEventGamepadEventAdapter observers]
+ -[_GCCollectionEventGamepadEventAdapter setObservers:]
+ -[_GCCollectionEventGamepadEventAdapterConfig .cxx_destruct]
+ -[_GCCollectionEventGamepadEventAdapterConfig applyCollectionEvent:toExtendedEvent:]
+ -[_GCCollectionEventGamepadEventAdapterConfig encodeWithCoder:]
+ -[_GCCollectionEventGamepadEventAdapterConfig initWithCoder:]
+ -[_GCCollectionEventGamepadEventAdapterConfig init]
+ -[_GCCollectionEventGamepadEventAdapterConfig mapAxisKey:toPositiveGamepadElement:negativeGamepadElement:]
+ -[_GCCollectionEventGamepadEventAdapterConfig mapKey:toGamepadElement:]
+ -[_GCCollectionEventGamepadEventAdapterDescription .cxx_destruct]
+ -[_GCCollectionEventGamepadEventAdapterDescription encodeWithCoder:]
+ -[_GCCollectionEventGamepadEventAdapterDescription initWithCoder:]
+ -[_GCCollectionEventGamepadEventAdapterDescription initWithConfiguration:source:]
+ -[_GCCollectionEventGamepadEventAdapterDescription init]
+ -[_GCCollectionEventGamepadEventAdapterDescription materializeWithContext:]
+ -[_GCNintendoFusedJoyConHapticDriver endHaptics]
+ _GCFLOC_BUTTON_L5
+ _GCFLOC_BUTTON_R5
+ _GCProductCategorySteam
+ _OBJC_CLASS_$__GCCollectionEventGamepadEventAdapter
+ _OBJC_CLASS_$__GCCollectionEventGamepadEventAdapterConfig
+ _OBJC_CLASS_$__GCCollectionEventGamepadEventAdapterDescription
+ _OBJC_CLASS_$__GCSteam2ControllerProfile
+ _OBJC_IVAR_$__GCCollectionEventGamepadEventAdapter._config
+ _OBJC_IVAR_$__GCCollectionEventGamepadEventAdapter._observation
+ _OBJC_IVAR_$__GCCollectionEventGamepadEventAdapter._observers
+ _OBJC_IVAR_$__GCCollectionEventGamepadEventAdapterConfig._axisMappings
+ _OBJC_IVAR_$__GCCollectionEventGamepadEventAdapterConfig._buttonMappings
+ _OBJC_IVAR_$__GCCollectionEventGamepadEventAdapterDescription._config
+ _OBJC_IVAR_$__GCCollectionEventGamepadEventAdapterDescription._materializedObject
+ _OBJC_IVAR_$__GCCollectionEventGamepadEventAdapterDescription._sourceDescription
+ _OBJC_METACLASS_$__GCCollectionEventGamepadEventAdapter
+ _OBJC_METACLASS_$__GCCollectionEventGamepadEventAdapterConfig
+ _OBJC_METACLASS_$__GCCollectionEventGamepadEventAdapterDescription
+ _OBJC_METACLASS_$__GCSteam2ControllerProfile
+ __OBJC_$_CLASS_METHODS__GCCollectionEventGamepadEventAdapterConfig
+ __OBJC_$_CLASS_METHODS__GCCollectionEventGamepadEventAdapterDescription
+ __OBJC_$_CLASS_METHODS__GCSteam2ControllerProfile
+ __OBJC_$_CLASS_PROP_LIST__GCCollectionEventGamepadEventAdapterConfig
+ __OBJC_$_CLASS_PROP_LIST__GCCollectionEventGamepadEventAdapterDescription
+ __OBJC_$_CLASS_PROP_LIST__GCSteam2ControllerProfile
+ __OBJC_$_INSTANCE_METHODS__GCCollectionEventGamepadEventAdapter
+ __OBJC_$_INSTANCE_METHODS__GCCollectionEventGamepadEventAdapterConfig
+ __OBJC_$_INSTANCE_METHODS__GCCollectionEventGamepadEventAdapterDescription
+ __OBJC_$_INSTANCE_VARIABLES__GCCollectionEventGamepadEventAdapter
+ __OBJC_$_INSTANCE_VARIABLES__GCCollectionEventGamepadEventAdapterConfig
+ __OBJC_$_INSTANCE_VARIABLES__GCCollectionEventGamepadEventAdapterDescription
+ __OBJC_$_PROP_LIST__GCCollectionEventGamepadEventAdapter
+ __OBJC_$_PROP_LIST__GCCollectionEventGamepadEventAdapterDescription
+ __OBJC_$_PROP_LIST__GCSteam2ControllerProfile
+ __OBJC_CLASS_PROTOCOLS_$__GCCollectionEventGamepadEventAdapter
+ __OBJC_CLASS_PROTOCOLS_$__GCCollectionEventGamepadEventAdapterConfig
+ __OBJC_CLASS_PROTOCOLS_$__GCCollectionEventGamepadEventAdapterDescription
+ __OBJC_CLASS_PROTOCOLS_$__GCSteam2ControllerProfile
+ __OBJC_CLASS_RO_$__GCCollectionEventGamepadEventAdapter
+ __OBJC_CLASS_RO_$__GCCollectionEventGamepadEventAdapterConfig
+ __OBJC_CLASS_RO_$__GCCollectionEventGamepadEventAdapterDescription
+ __OBJC_CLASS_RO_$__GCSteam2ControllerProfile
+ __OBJC_METACLASS_RO_$__GCCollectionEventGamepadEventAdapter
+ __OBJC_METACLASS_RO_$__GCCollectionEventGamepadEventAdapterConfig
+ __OBJC_METACLASS_RO_$__GCCollectionEventGamepadEventAdapterDescription
+ __OBJC_METACLASS_RO_$__GCSteam2ControllerProfile
+ ___110+[_GCSpatialDeviceProfile logicalDevice:makeControllerPhysicalInputProfileDescriptionWithIdentifier:bindings:]_block_invoke
+ ___43+[_GCSteam2ControllerProfile deviceManager]_block_invoke
+ ___62-[_GCCollectionEventGamepadEventAdapter observeGamepadEvents:]_block_invoke
+ ___70-[_GCCollectionEventGamepadEventAdapter initWithConfiguration:source:]_block_invoke
+ ___84-[_GCCollectionEventGamepadEventAdapterConfig applyCollectionEvent:toExtendedEvent:]_block_invoke
+ ___84-[_GCCollectionEventGamepadEventAdapterConfig applyCollectionEvent:toExtendedEvent:]_block_invoke_2
+ ___block_descriptor_48_e8_32s_e34_v32?0"NSNumber"8"NSArray"16^B24ls32l8
+ ___block_descriptor_48_e8_32s_e35_v32?0"NSNumber"8"NSNumber"16^B24ls32l8
+ ___block_descriptor_56_e8_32s40s48r_e41_"_GCHIDEventParser"16?0"NSDictionary"8lr48l8s32l8s40l8
+ ___block_descriptor_64_e8_32s40s48w_e20_v24?08"NSError"16lw48l8s32l8s40l8
+ ___block_descriptor_64_e8_32s40s48w_e5_v8?0ls32l8s40l8w48l8
+ ___os_log_helper_16_0_0
+ ___os_log_helper_16_2_1_8_66
+ ___os_log_helper_16_2_2_8_34_8_0
+ ___os_log_helper_16_2_2_8_66_8_64
+ ___os_log_helper_16_2_3_8_0_8_0_8_32
CStrings:
+ "AC Power"
+ "Steam Controller"
+ "TwoHandleHapticCapabilityGraph"
+ "axisMappings"
+ "button.l4"
+ "button.l5"
+ "button.r4"
+ "button.r5"
+ "buttonMappings"
+ "steamcontroller2"
```
