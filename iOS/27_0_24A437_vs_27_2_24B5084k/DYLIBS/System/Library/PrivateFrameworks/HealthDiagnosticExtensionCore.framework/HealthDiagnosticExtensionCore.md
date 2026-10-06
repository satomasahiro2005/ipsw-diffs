## HealthDiagnosticExtensionCore

> `/System/Library/PrivateFrameworks/HealthDiagnosticExtensionCore.framework/HealthDiagnosticExtensionCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbdd4` | `0xb138` | **`-0xc9c`** |
| `__AUTH_CONST.__cfstring` | `0x2700` | `0x2500` | **`-0x200`** |
| `__TEXT.__cstring` | `0x2806` | `0x26bb` | **`-0x14b`** |
| `__DATA_CONST.__objc_selrefs` | `0x8d0` | `0x810` | **`-0xc0`** |
| `__AUTH_CONST.__objc_const` | `0x918` | `0x888` | **`-0x90`** |
| `__TEXT.__objc_methlist` | `0x6fc` | `0x684` | **`-0x78`** |
| `__AUTH.__objc_data` | `0x420` | `0x3d0` | **`-0x50`** |
| `__AUTH_CONST.__auth_got` | `0x3e8` | `0x398` | **`-0x50`** |
| `__DATA_CONST.__const` | `0x5c0` | `0x598` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0x348` | `0x320` | **`-0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x60` | `0x58` | **`-0x8`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

-  - /System/Library/PrivateFrameworks/RegulatoryDomain.framework/RegulatoryDomain

-  Functions: 194
-  Symbols:   593
-  CStrings:  350
+  Functions: 184
+  Symbols:   565
+  CStrings:  334
Symbols:
- -[HDFeatureStatusDiagnosticOperation _reportCountryCodeOverride]
- -[HDFeatureStatusDiagnosticOperation _reportCountryCodeSource]
- -[HDFeatureStatusDiagnosticOperation _reportFeatureStatusByFeature]
- -[HDFeatureStatusDiagnosticOperation _reportFeatureStatusForFeature:healthStore:]
- -[HDFeatureStatusDiagnosticOperation _reportRegionAvailabilityByFeature]
- -[HDFeatureStatusDiagnosticOperation _reportRegionAvailabilityForFeature:healthStore:]
- -[HDFeatureStatusDiagnosticOperation _reportRequirementSatisfactionOverridesByFeature]
- -[HDFeatureStatusDiagnosticOperation reportFilename]
- -[HDFeatureStatusDiagnosticOperation run]
- _HKAllFeatureIdentifiers
- _HKFeatureIdentifierAFibBurden
- _HKPreferredRegulatoryDomainProvider
- _HKPrettyPrintedFeatureStatus
- _HKRegulatoryDomainEstimateOverrideISOCode
- _NSStringFromHKOnboardingCompletionCountryCodeProvenance
- _OBJC_CLASS_$_HDFeatureStatusDiagnosticOperation
- _OBJC_CLASS_$_HKFeatureAvailabilityRequirementSatisfactionOverrides
- _OBJC_CLASS_$_HKFeatureStatusManager
- _OBJC_CLASS_$_RDEstimate
- _OBJC_METACLASS_$_HDFeatureStatusDiagnosticOperation
- __OBJC_$_INSTANCE_METHODS_HDFeatureStatusDiagnosticOperation
- __OBJC_CLASS_RO_$_HDFeatureStatusDiagnosticOperation
- __OBJC_METACLASS_RO_$_HDFeatureStatusDiagnosticOperation
- ___86-[HDFeatureStatusDiagnosticOperation _reportRequirementSatisfactionOverridesByFeature]_block_invoke
- ___block_descriptor_40_e8_32s_e31_v24?0"NSString"8"NSString"16ls32l8
- _objc_retainAutoreleasedReturnValue
- _objc_retain_x28
- _swift_bridgeObjectRelease
CStrings:
+ "HealthTypes Enabled: true\n"
- "%@ (%@)"
- "%@:"
- "<none>"
- "<redacted>"
- "Country Code Information"
- "Country Code Override"
- "Error evaluating feature status for %@: %@"
- "Error evaluating region availability for %@: %@"
- "Feature Status"
- "HKRegulatoryDomainEstimate"
- "HealthFeatureStatus.txt"
- "HealthTypes Enabled: "
- "RDEstimate.currentEstimates"
- "Region Availability"
- "Requirement Satisfaction Overrides"
- "Retrieved: %@"
- "nil"
```
