## HealthFeaturesDiagnosticExtensionPlugin

> `/System/Library/Health/DiagnosticExtensionPlugins/HealthFeaturesDiagnosticExtensionPlugin.bundle/HealthFeaturesDiagnosticExtensionPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1734` | `0x4550` | **`+0x2e1c`** |
| `__DATA.__bss` | `—` | `0x600` | **`+0x600`** |
| `__TEXT.__const` | `0x10a` | `0x448` | **`+0x33e`** |
| `__TEXT.__objc_stubs` | `0x260` | `0x480` | **`+0x220`** |
| `__TEXT.__auth_stubs` | `0x4b0` | `0x6b0` | **`+0x200`** |
| `__TEXT.__objc_methname` | `0x1da` | `0x374` | **`+0x19a`** |
| `__TEXT.__eh_frame` | `—` | `0x150` | **`+0x150`** |
| `__TEXT.__cstring` | `0x7d` | `0x1c8` | **`+0x14b`** |
| `__DATA_CONST.__auth_got` | `0x260` | `0x360` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0xa0` | `0x178` | **`+0xd8`** |
| `__DATA.__data` | `0xf0` | `0x1a8` | **`+0xb8`** |
| `__DATA_CONST.__auth_ptr` | `0x10` | `0xc8` | **`+0xb8`** |
| `__DATA.__objc_data` | `0x160` | `0x210` | **`+0xb0`** |
| `__DATA.__objc_selrefs` | `0xb8` | `0x140` | **`+0x88`** |
| `__TEXT.__constg_swiftt` | `0x64` | `0xdc` | **`+0x78`** |
| `__TEXT.__swift5_typeref` | `0x52` | `0xc8` | **`+0x76`** |
| `__DATA_CONST.__got` | `0x90` | `0xf8` | **`+0x68`** |
| `__DATA.__objc_const` | `0xd0` | `0x130` | **`+0x60`** |
| `__DATA_CONST.__const` | `0xe8` | `0x148` | **`+0x60`** |
| `__TEXT.__swift5_assocty` | `—` | `0x60` | **`+0x60`** |
| `__TEXT.__objc_classname` | `0x76` | `0xc6` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x20` | `0x68` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x64` | `0x94` | **`+0x30`** |
| `__TEXT.__swift5_proto` | `—` | `0x30` | **`+0x30`** |
| `__TEXT.__swift5_builtin` | `—` | `0x28` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `—` | `0x23` | **`+0x23`** |
| `__TEXT.__swift5_types` | `0x8` | `0x14` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x10` | `0x18` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_capture`

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

+  - /System/Library/PrivateFrameworks/RegulatoryDomain.framework/RegulatoryDomain

+  - /usr/lib/swift/libswiftCompression.dylib

+  - /usr/lib/swift/libswiftOSLog.dylib

-  Functions: 22
-  Symbols:   67
-  CStrings:  36
+  Functions: 91
+  Symbols:   94
+  CStrings:  63
Symbols:
+ _HKAllFeatureIdentifiers
+ _HKFeatureIdentifierAFibBurden
+ _HKPreferredRegulatoryDomainProvider
+ _HKPrettyPrintedFeatureStatus
+ _NSStringFromHKOnboardingCompletionCountryCodeProvenance
+ _OBJC_CLASS_$_HKFeatureAvailabilityRequirementSatisfactionOverrides
+ _OBJC_CLASS_$_HKFeatureStatusManager
+ _OBJC_CLASS_$_HKRegulatoryDomainManager
+ _OBJC_CLASS_$_RDEstimate
+ __swiftEmptyArrayStorage
+ __swift_FORCE_LOAD_$_swiftCompression
+ __swift_FORCE_LOAD_$_swiftOSLog
+ _malloc_size
+ _memcpy
+ _memmove
+ _objc_release_x26
+ _objc_retain_x21
+ _objc_retain_x23
+ _swift_arrayInitWithCopy
+ _swift_bridgeObjectRetain
+ _swift_getErrorValue
+ _swift_getForeignTypeMetadata
+ _swift_getWitnessTable
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_release_x19
+ _swift_release_x22
+ _swift_release_x8
CStrings:
+ "Country Code Information"
+ "Country Code Override"
+ "Error evaluating feature status for "
+ "Error evaluating region availability for "
+ "HKRegulatoryDomainEstimate"
+ "HealthFeatureStatus.txt"
+ "ISOCode"
+ "RDEstimate.currentEstimates"
+ "Region Availability"
+ "Requirement Satisfaction Overrides"
+ "_TtC39HealthFeaturesDiagnosticExtensionPlugin32FeatureStatusDiagnosticOperation"
+ "appendNewline"
+ "appendRow:"
+ "boolValue"
+ "currentEstimate"
+ "currentEstimates"
+ "featureAvailabilityProvidingForFeatureIdentifier:"
+ "featureStatusWithError:"
+ "initWithFeatureIdentifier:"
+ "initWithFeatureIdentifier:healthStore:"
+ "overriddenRequirementIdentifiers"
+ "overriddenSatisfactionOfRequirementWithIdentifier:"
+ "overrideISOCountryCode"
+ "prettyPrintedDescription"
+ "provenance"
+ "regionAvailabilityWithError:"
+ "timestamp"
```
