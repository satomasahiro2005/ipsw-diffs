## MentalHealthDaemon

> `/System/Library/PrivateFrameworks/MentalHealthDaemon.framework/MentalHealthDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18b3c` | `0x1a578` | **`+0x1a3c`** |
| `__DATA.__bss` | `0x190` | `0x490` | **`+0x300`** |
| `__TEXT.__const` | `0x450` | `0x624` | **`+0x1d4`** |
| `__DATA.__data` | `0xa90` | `0xb48` | **`+0xb8`** |
| `__AUTH_CONST.__objc_const` | `0x2670` | `0x2708` | **`+0x98`** |
| `__TEXT.__unwind_info` | `0x778` | `0x810` | **`+0x98`** |
| `__AUTH_CONST.__auth_got` | `0x5f8` | `0x678` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x1664` | `0x16c4` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x82` | `0xce` | **`+0x4c`** |
| `__TEXT.__eh_frame` | `—` | `0x48` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x1078` | `0x10a8` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x18` | `0x48` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x2f8` | `0x320` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x268` | `0x288` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x96` | `0xb6` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x8c` | `0xa8` | **`+0x1c`** |
| `__TEXT.__swift5_proto` | `0xc` | `0x24` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x50` | `0x64` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x510` | `0x520` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0xe8` | `0xf8` | **`+0x10`** |
| `__DATA_CONST.__objc_catlist` | `0x18` | `0x20` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x20` | `0x28` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x18` | `0x1c` | **`+0x4`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

+  - /System/Library/PrivateFrameworks/HealthFeatures.framework/HealthFeatures

-  Functions: 560
-  Symbols:   1176
+  Functions: 610
+  Symbols:   1197
Symbols:
+ +[HDFeatureAvailabilityManager(HDMentalHealth) _hdmh_availabilityManagerForFeatureIdentifier:profile:availabilityRequirements:localCountrySet:]
+ __CATEGORY_CLASS_METHODS_HKFeatureAvailabilityRequirementSet_$_MentalHealthDaemon
+ __CATEGORY_CLASS_PROPERTIES_HKFeatureAvailabilityRequirementSet_$_MentalHealthDaemon
+ __CATEGORY_HKFeatureAvailabilityRequirementSet_$_MentalHealthDaemon
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HKFeatureAvailabilityRequirementsProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HKFeatureAvailabilityRequirementsProviding
+ __OBJC_LABEL_PROTOCOL_$_HKFeatureAvailabilityRequirementsProviding
+ __OBJC_PROTOCOL_$_HKFeatureAvailabilityRequirementsProviding
+ _associated conformance So28HKFeatureAvailabilityContextaSHSCSQ
+ _associated conformance So28HKFeatureAvailabilityContextas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So28HKFeatureAvailabilityContextas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _swift_arrayInitWithCopy
+ _swift_getExistentialTypeMetadata
+ _swift_getTupleTypeMetadata2
+ _swift_initStackObject
+ _swift_isUniquelyReferenced_nonNull_bridgeObject
+ _swift_release_x26
+ _symbolic $ss21_ObjectiveCBridgeableP
+ _symbolic SS
+ _symbolic So8NSStringC
+ _symbolic _____ So28HKFeatureAvailabilityContexta
+ _type_layout_string So28HKFeatureAvailabilityContexta
- +[HDFeatureAvailabilityManager(HDMentalHealth) _hdmc_availabilityManagerForFeatureIdentifier:profile:availabilityRequirements:localCountrySet:]
```
