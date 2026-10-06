## HealthHearingDaemon

> `/System/Library/PrivateFrameworks/HealthHearingDaemon.framework/HealthHearingDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20b18` | `0x225e0` | **`+0x1ac8`** |
| `__DATA.__bss` | `0x300` | `0x600` | **`+0x300`** |
| `__DATA.__data` | `0x910` | `0xb90` | **`+0x280`** |
| `__TEXT.__const` | `0x3f2` | `0x5a0` | **`+0x1ae`** |
| `__TEXT.__objc_methlist` | `0x1b1c` | `0x1bec` | **`+0xd0`** |
| `__AUTH_CONST.__auth_got` | `0x620` | `0x6c8` | **`+0xa8`** |
| `__AUTH_CONST.__objc_const` | `0x3068` | `0x3110` | **`+0xa8`** |
| `__TEXT.__unwind_info` | `0x780` | `0x808` | **`+0x88`** |
| `__DATA_CONST.__objc_selrefs` | `0x17b8` | `0x1838` | **`+0x80`** |
| `__DATA_CONST.__objc_protolist` | `0xd0` | `0x120` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x80` | `0xc8` | **`+0x48`** |
| `__TEXT.__swift5_assocty` | `0x30` | `0x60` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x310` | `0x338` | **`+0x28`** |
| `__DATA_CONST.__objc_protorefs` | `0x20` | `0x48` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x1d20` | `0x1d00` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x4f0` | `0x510` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0xd8` | `0xf8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x21c4` | `0x21a4` | **`-0x20`** |
| `__TEXT.__swift5_typeref` | `0xbc` | `0xd9` | **`+0x1d`** |
| `__TEXT.__swift5_fieldmd` | `0x74` | `0x90` | **`+0x1c`** |
| `__TEXT.__swift5_proto` | `0x18` | `0x30` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x14` | `0x28` | **`+0x14`** |
| `__DATA_DIRTY.__data` | `0xd0` | `0xc0` | **`-0x10`** |
| `__DATA_CONST.__objc_catlist` | `0x38` | `0x30` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x8` | `0xc` | **`+0x4`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

+  - /System/Library/PrivateFrameworks/OSEligibility.framework/OSEligibility

-  Functions: 697
-  Symbols:   1331
-  CStrings:  440
+  Functions: 756
+  Symbols:   1366
+  CStrings:  439
Symbols:
+ _HKFeatureAvailabilityContextHearingAidProvincialUsage
+ __OBJC_$_CLASS_METHODS_HKFeatureAvailabilityRequirementSet(Hearing|HealthHearingDaemon)
+ __OBJC_$_CLASS_PROP_LIST_HKFeatureAvailabilityRequirement
+ __OBJC_$_CLASS_PROP_LIST_NSSecureCoding
+ __OBJC_$_PROP_LIST_HKFeatureAvailabilityRequirement
+ __OBJC_$_PROTOCOL_CLASS_METHODS_HKFeatureAvailabilityRequirement
+ __OBJC_$_PROTOCOL_CLASS_METHODS_NSSecureCoding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HKFeatureAvailabilityRequirement
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HKFeatureAvailabilityRequirementsProviding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NSCoding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NSCopying
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HKFeatureAvailabilityRequirement
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HKFeatureAvailabilityRequirementsProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSCoding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSCopying
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSSecureCoding
+ __OBJC_$_PROTOCOL_REFS_HKFeatureAvailabilityRequirement
+ __OBJC_$_PROTOCOL_REFS_NSSecureCoding
+ __OBJC_LABEL_PROTOCOL_$_HKFeatureAvailabilityRequirement
+ __OBJC_LABEL_PROTOCOL_$_HKFeatureAvailabilityRequirementsProviding
+ __OBJC_LABEL_PROTOCOL_$_NSCoding
+ __OBJC_LABEL_PROTOCOL_$_NSCopying
+ __OBJC_LABEL_PROTOCOL_$_NSSecureCoding
+ __OBJC_PROTOCOL_$_HKFeatureAvailabilityRequirement
+ __OBJC_PROTOCOL_$_HKFeatureAvailabilityRequirementsProviding
+ __OBJC_PROTOCOL_$_NSCoding
+ __OBJC_PROTOCOL_$_NSCopying
+ __OBJC_PROTOCOL_$_NSSecureCoding
+ _associated conformance So28HKFeatureAvailabilityContextaSHSCSQ
+ _associated conformance So28HKFeatureAvailabilityContextas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So28HKFeatureAvailabilityContextas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _swift_arrayDestroy
+ _swift_arrayInitWithCopy
+ _swift_bridgeObjectRelease_n
+ _swift_dynamicCastMetatype
+ _swift_dynamicCastObjCProtocolConditional
+ _swift_getTupleTypeMetadata2
+ _swift_initStackObject
+ _swift_isUniquelyReferenced_nonNull_bridgeObject
+ _swift_release_x20
+ _swift_release_x26
+ _swift_retain_x20
+ _swift_retain_x22
+ _symbolic _____ So28HKFeatureAvailabilityContexta
+ _type_layout_string So28HKFeatureAvailabilityContexta
- +[HKFeatureAvailabilityRequirementSet advertisableFeatureRequirementsForIdentifier:]
- +[HKFeatureAvailabilityRequirementSet promptTileRequirementsForIdentifier:]
- +[HKFeatureAvailabilityRequirementSet settingsUserInteractionEnabledRequirementsForIdentifier:]
- +[HKFeatureAvailabilityRequirementSet settingsVisibilityRequirementsForIdentifier:]
- +[HKFeatureAvailabilityRequirementSet usageRequirementsForIdentifier:]
- +[HKFeatureAvailabilityRequirements(Hearing) hearingFeatureHardwareRequirementsForFeatureIdentifier:]
- __OBJC_$_CATEGORY_CLASS_METHODS_HKFeatureAvailabilityRequirementSet_$_Hearing
- __OBJC_$_CATEGORY_CLASS_METHODS_HKFeatureAvailabilityRequirements_$_Hearing
- __OBJC_$_CATEGORY_HKFeatureAvailabilityRequirements_$_Hearing
- _type_layout_string So42HKFeatureAvailabilityRequirementIdentifiera
CStrings:
+ "com.apple.health.demo-watch"
- "AAAAAAAA-AAAA-AAAA-AAAA-AAAAAAAAAAAA"
- "com.apple.health.demo_watch"
```
