## AdCore

> `/System/Library/PrivateFrameworks/AdCore.framework/AdCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x6c40` | `0x7a88` | **`+0xe48`** |
| `__TEXT.__text` | `0x31670` | `0x31f08` | **`+0x898`** |
| `__TEXT.__objc_methlist` | `0x42d4` | `0x4494` | **`+0x1c0`** |
| `__AUTH.__objc_data` | `0x460` | `0x5f0` | **`+0x190`** |
| `__DATA.__data` | `0x300` | `0x420` | **`+0x120`** |
| `__DATA_CONST.__objc_selrefs` | `0x20f8` | `0x2198` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x4da0` | `0x4e00` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0xc90` | `0xcd8` | **`+0x48`** |
| `__TEXT.__cstring` | `0x405d` | `0x40a2` | **`+0x45`** |
| `__DATA_CONST.__got` | `0x390` | `0x3c8` | **`+0x38`** |
| `__DATA_CONST.__objc_classlist` | `0x188` | `0x1b0` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x418` | `0x434` | **`+0x1c`** |
| `__DATA_CONST.__objc_protolist` | `0x40` | `0x58` | **`+0x18`** |
| `__DATA.__bss` | `0x10` | `—` | **`-0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x178` | `0x188` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x240` | `0x250` | **`+0x10`** |

### Other Changes

```diff

-638.2.0.0.0
+638.2.2.0.0

-  Functions: 1454
-  Symbols:   2495
-  CStrings:  661
+  Functions: 1481
+  Symbols:   2583
+  CStrings:  664
Symbols:
+ +[ADAccountQualityDiagnosticSample sampleWithBirthYearValidity:personalizedAdsStatus:storefrontID:]
+ +[ADAccountQualityDiagnostics(Production) production]
+ -[ADAccountQualityDiagnosticSample .cxx_destruct]
+ -[ADAccountQualityDiagnosticSample birthYearValidity]
+ -[ADAccountQualityDiagnosticSample initWithBirthYearValidity:personalizedAdsStatus:storefrontID:]
+ -[ADAccountQualityDiagnosticSample personalizedAdsStatus]
+ -[ADAccountQualityDiagnosticSample setBirthYearValidity:]
+ -[ADAccountQualityDiagnosticSample setPersonalizedAdsStatus:]
+ -[ADAccountQualityDiagnosticSample setStorefrontID:]
+ -[ADAccountQualityDiagnosticSample storefrontID]
+ -[ADAccountQualityDiagnostics .cxx_destruct]
+ -[ADAccountQualityDiagnostics birthYearValidityForAccount:]
+ -[ADAccountQualityDiagnostics birthYearValidityForConsumerAccount:]
+ -[ADAccountQualityDiagnostics birthYearValidityForRestrictedAccount:]
+ -[ADAccountQualityDiagnostics captureAccount:]
+ -[ADAccountQualityDiagnostics clock]
+ -[ADAccountQualityDiagnostics depot]
+ -[ADAccountQualityDiagnostics initWithClock:depot:personalizedAdsSource:storefrontIDSource:]
+ -[ADAccountQualityDiagnostics personalizedAdsSource]
+ -[ADAccountQualityDiagnostics storefrontIDSource]
+ -[ADCoreAnalyticsAccountQualityDiagnosticDepot depositSample:]
+ -[ADCoreSettingsPersonalizedAdsSource personalizedAds]
+ -[ADSystemClock now]
+ -[DSIDRecord(Helpers) isConsumer]
+ -[DSIDRecord(Helpers) isRestricted]
+ _NSCalendarIdentifierGregorian
+ _OBJC_CLASS_$_ADAccountQualityDiagnosticSample
+ _OBJC_CLASS_$_ADAccountQualityDiagnostics
+ _OBJC_CLASS_$_ADCoreAnalyticsAccountQualityDiagnosticDepot
+ _OBJC_CLASS_$_ADCoreSettingsPersonalizedAdsSource
+ _OBJC_CLASS_$_ADSystemClock
+ _OBJC_CLASS_$_NSCalendar
+ _OBJC_IVAR_$_ADAccountQualityDiagnosticSample._birthYearValidity
+ _OBJC_IVAR_$_ADAccountQualityDiagnosticSample._personalizedAdsStatus
+ _OBJC_IVAR_$_ADAccountQualityDiagnosticSample._storefrontID
+ _OBJC_IVAR_$_ADAccountQualityDiagnostics._clock
+ _OBJC_IVAR_$_ADAccountQualityDiagnostics._depot
+ _OBJC_IVAR_$_ADAccountQualityDiagnostics._personalizedAdsSource
+ _OBJC_IVAR_$_ADAccountQualityDiagnostics._storefrontIDSource
+ _OBJC_METACLASS_$_ADAccountQualityDiagnosticSample
+ _OBJC_METACLASS_$_ADAccountQualityDiagnostics
+ _OBJC_METACLASS_$_ADCoreAnalyticsAccountQualityDiagnosticDepot
+ _OBJC_METACLASS_$_ADCoreSettingsPersonalizedAdsSource
+ _OBJC_METACLASS_$_ADSystemClock
+ __OBJC_$_CLASS_METHODS_ADAccountQualityDiagnosticSample
+ __OBJC_$_CLASS_METHODS_ADAccountQualityDiagnostics(Production)
+ __OBJC_$_INSTANCE_METHODS_ADAccountQualityDiagnosticSample
+ __OBJC_$_INSTANCE_METHODS_ADAccountQualityDiagnostics
+ __OBJC_$_INSTANCE_METHODS_ADCoreAnalyticsAccountQualityDiagnosticDepot
+ __OBJC_$_INSTANCE_METHODS_ADCoreSettingsPersonalizedAdsSource
+ __OBJC_$_INSTANCE_METHODS_ADSystemClock
+ __OBJC_$_INSTANCE_METHODS_DSIDRecord(Helpers)
+ __OBJC_$_INSTANCE_VARIABLES_ADAccountQualityDiagnosticSample
+ __OBJC_$_INSTANCE_VARIABLES_ADAccountQualityDiagnostics
+ __OBJC_$_PROP_LIST_ADAccountQualityDiagnosticSample
+ __OBJC_$_PROP_LIST_ADAccountQualityDiagnostics
+ __OBJC_$_PROP_LIST_ADCoreAnalyticsAccountQualityDiagnosticDepot
+ __OBJC_$_PROP_LIST_ADCoreSettingsPersonalizedAdsSource
+ __OBJC_$_PROP_LIST_ADSystemClock
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_ADAccountQualityDiagnosticDepot
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_ADClock
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_ADPersonalizedAdsSource
+ __OBJC_$_PROTOCOL_METHOD_TYPES_ADAccountQualityDiagnosticDepot
+ __OBJC_$_PROTOCOL_METHOD_TYPES_ADClock
+ __OBJC_$_PROTOCOL_METHOD_TYPES_ADPersonalizedAdsSource
+ __OBJC_$_PROTOCOL_REFS_ADAccountQualityDiagnosticDepot
+ __OBJC_$_PROTOCOL_REFS_ADClock
+ __OBJC_$_PROTOCOL_REFS_ADPersonalizedAdsSource
+ __OBJC_CLASS_PROTOCOLS_$_ADCoreAnalyticsAccountQualityDiagnosticDepot
+ __OBJC_CLASS_PROTOCOLS_$_ADCoreSettingsPersonalizedAdsSource
+ __OBJC_CLASS_PROTOCOLS_$_ADSystemClock
+ __OBJC_CLASS_RO_$_ADAccountQualityDiagnosticSample
+ __OBJC_CLASS_RO_$_ADAccountQualityDiagnostics
+ __OBJC_CLASS_RO_$_ADCoreAnalyticsAccountQualityDiagnosticDepot
+ __OBJC_CLASS_RO_$_ADCoreSettingsPersonalizedAdsSource
+ __OBJC_CLASS_RO_$_ADSystemClock
+ __OBJC_LABEL_PROTOCOL_$_ADAccountQualityDiagnosticDepot
+ __OBJC_LABEL_PROTOCOL_$_ADClock
+ __OBJC_LABEL_PROTOCOL_$_ADPersonalizedAdsSource
+ __OBJC_METACLASS_RO_$_ADAccountQualityDiagnosticSample
+ __OBJC_METACLASS_RO_$_ADAccountQualityDiagnostics
+ __OBJC_METACLASS_RO_$_ADCoreAnalyticsAccountQualityDiagnosticDepot
+ __OBJC_METACLASS_RO_$_ADCoreSettingsPersonalizedAdsSource
+ __OBJC_METACLASS_RO_$_ADSystemClock
+ __OBJC_PROTOCOL_$_ADAccountQualityDiagnosticDepot
+ __OBJC_PROTOCOL_$_ADClock
+ __OBJC_PROTOCOL_$_ADPersonalizedAdsSource
+ ___62-[ADCoreAnalyticsAccountQualityDiagnosticDepot depositSample:]_block_invoke
+ _currentYear
- __OBJC_$_INSTANCE_METHODS_DSIDRecord
CStrings:
+ "PAStatus"
+ "birthYearValidity"
+ "com.apple.ap.adprivacyd.account.quality"
```
