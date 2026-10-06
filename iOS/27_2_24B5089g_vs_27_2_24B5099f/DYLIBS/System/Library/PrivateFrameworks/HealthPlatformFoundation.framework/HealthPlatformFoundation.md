## HealthPlatformFoundation

> `/System/Library/PrivateFrameworks/HealthPlatformFoundation.framework/HealthPlatformFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5baf4` | `0x62f9c` | **`+0x74a8`** |
| `__TEXT.__cstring` | `0x82f` | `0xcaf` | **`+0x480`** |
| `__TEXT.__oslogstring` | `0xcf8` | `0xf48` | **`+0x250`** |
| `__DATA_CONST.__got` | `0x510` | `0x6c0` | **`+0x1b0`** |
| `__TEXT.__const` | `0x35ac` | `0x36dc` | **`+0x130`** |
| `__DATA.__bss` | `0x3a20` | `0x3b10` | **`+0xf0`** |
| `__DATA.__data` | `0x8f0` | `0x9c0` | **`+0xd0`** |
| `__AUTH_CONST.__const` | `0x20f8` | `0x21b8` | **`+0xc0`** |
| `__TEXT.__eh_frame` | `0x2320` | `0x23e0` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0x17b8` | `0x1830` | **`+0x78`** |
| `__AUTH_CONST.__auth_got` | `0xcc8` | `0xd30` | **`+0x68`** |
| `__TEXT.__swift5_fieldmd` | `0x1120` | `0x116c` | **`+0x4c`** |
| `__TEXT.__swift5_reflstr` | `0xdbf` | `0xdff` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0xce8` | `0xd08` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x1120` | `0x113c` | **`+0x1c`** |
| `__TEXT.__swift5_typeref` | `0xe31` | `0xe4b` | **`+0x1a`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x3c` | **`+0x14`** |
| `__TEXT.__swift5_capture` | `0x134` | `0x144` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x180` | `0x188` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0x8` | `0x10` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x294` | `0x29c` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x138` | `0x13c` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x148` | `0x14c` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0xc8` | `0xcc` | **`+0x4`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

+  - /System/Library/PrivateFrameworks/HealthUtilities.framework/HealthUtilities

-  Functions: 2012
-  Symbols:   633
-  CStrings:  122
+  Functions: 2076
+  Symbols:   642
+  CStrings:  163
Symbols:
+ _get_enum_tag_for_layout_string 24HealthPlatformFoundation0A37AppIntelligenceAvailabilitySimulationV4ModeO
+ _kHKAppleIntelligenceAvailabilitySimulation
+ _kHKAppleIntelligenceConfigurationHeldEnabledState
+ _swift_retain_x8
+ _symbolic Say_____G 16FoundationModels19SystemLanguageModelC20InternalAvailabilityO14RestrictedInfoV0H6ReasonO
+ _symbolic Shy_____G 16FoundationModels19SystemLanguageModelC20InternalAvailabilityO15UnavailableInfoV0H6ReasonO
+ _symbolic _____ 24HealthPlatformFoundation0A37AppIntelligenceAvailabilitySimulationV
+ _symbolic _____ 24HealthPlatformFoundation0A37AppIntelligenceAvailabilitySimulationV4ModeO
+ _symbolic _____Sg 15HealthUtilities20SendableUserDefaultsC
+ _symbolic _____ySbSgGSg 15HealthUtilities21ObservableUserDefaultC
+ _type_layout_string 24HealthPlatformFoundation0A37AppIntelligenceAvailabilitySimulationV
+ _type_layout_string 24HealthPlatformFoundation0A37AppIntelligenceAvailabilitySimulationV4ModeO
- _swift_retain_x24
- _symbolic So14NSUserDefaultsCSg
- _symbolic _____ 24HealthPlatformFoundation0A24AppIntelligenceUtilitiesV
CStrings:
+ "Health App Intelligent Configuration availability simulated: %{public}s"
+ "Health App Intelligent Configuration is disabled for language identifier: %{public}s"
+ "Ignoring unparseable Health App Intelligent Configuration availability simulation: %{public}s"
+ "Model eligibility undetermined for language identifier: %{public}s; holding %{bool,public}d"
+ "No availability reported"
+ "Received undetermined restricted reasons: %s"
+ "Received undetermined unavailable reasons: %s"
+ "Recorded Health App Intelligent Configuration state: %{bool,public}d"
+ "Restricted with no reason given"
+ "Unavailable with no reason given"
+ "accessNotGranted"
+ "countryBillingIneligible"
+ "countryLocationIneligible"
+ "deviceClassIneligible"
+ "deviceIsInsecure"
+ "deviceNotCapable"
+ "externalBootDrive"
+ "externalIntelligenceNotAllowed"
+ "key value "
+ "localeIneligible"
+ "mdmAndParentalControl"
+ "noCacheForBaseUnavailableReasons"
+ "parentalRestriction"
+ "partnerNotSelected"
+ "pendingEnrollment"
+ "profileMisconfigured"
+ "regionIneligible"
+ "regionalSafetyAssetPendingUpdate"
+ "selectedLanguageDoesNotMatchSelectedSiriLanguage"
+ "selectedLanguageIneligible"
+ "selectedSiriLanguageIneligible"
+ "signInNotAllowed"
+ "siriAssetIsNotReady"
+ "siriAssetStatusUnknown"
+ "startupInProgress"
+ "unableToFetchAvailability"
+ "useCaseDoesNotAllowCurrentIPCountryCode"
+ "useCaseDoesNotAllowUserLocaleRegion"
+ "useCaseDoesNotSupportCurrentRegion"
+ "useCaseDoesNotSupportRequestedLanguage"
+ "useCaseDoesNotSupportSystemLanguage"
+ "workspaceNotAllowed"
- "No availability reported; treating as unavailable"
```
