## Setup

> `/Applications/Setup.app/Setup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x243658` | `0x24b3d0` | **`+0x7d78`** |
| `__TEXT.__oslogstring` | `0x148ae` | `0x14e3c` | **`+0x58e`** |
| `__TEXT.__objc_methname` | `0x4044e` | `0x409ae` | **`+0x560`** |
| `__DATA.__objc_const` | `0x49878` | `0x49d40` | **`+0x4c8`** |
| `__DATA_CONST.__const` | `0x8288` | `0x8708` | **`+0x480`** |
| `__DATA.__objc_data` | `0xc778` | `0xcb68` | **`+0x3f0`** |
| `__TEXT.__objc_stubs` | `0x29060` | `0x29380` | **`+0x320`** |
| `__DATA.__bss` | `0x1fa8` | `0x22a8` | **`+0x300`** |
| `__TEXT.__const` | `0x3360` | `0x3630` | **`+0x2d0`** |
| `__TEXT.__constg_swiftt` | `0x3780` | `0x3a14` | **`+0x294`** |
| `__TEXT.__objc_methlist` | `0x1daa8` | `0x1dd10` | **`+0x268`** |
| `__TEXT.__swift5_reflstr` | `0x1ab9` | `0x1ce9` | **`+0x230`** |
| `__TEXT.__swift5_typeref` | `0x2558` | `0x2788` | **`+0x230`** |
| `__TEXT.__eh_frame` | `0x40e0` | `0x4308` | **`+0x228`** |
| `__TEXT.__unwind_info` | `0x9c00` | `0x9e28` | **`+0x228`** |
| `__DATA.__data` | `0x77e0` | `0x7a00` | **`+0x220`** |
| `__TEXT.__swift5_fieldmd` | `0x18b4` | `0x1a2c` | **`+0x178`** |
| `__TEXT.__cstring` | `0xfbdb` | `0xfd2e` | **`+0x153`** |
| `__TEXT.__swift5_capture` | `0x10b0` | `0x11bc` | **`+0x10c`** |
| `__DATA.__objc_selrefs` | `0xcc30` | `0xcd00` | **`+0xd0`** |
| `__TEXT.__objc_methtype` | `0xca28` | `0xcaec` | **`+0xc4`** |
| `__TEXT.__objc_classname` | `0x5b88` | `0x5c43` | **`+0xbb`** |
| `__DATA_CONST.__cfstring` | `0xb4e0` | `0xb540` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x2890` | `0x28e0` | **`+0x50`** |
| `__DATA_CONST.__auth_ptr` | `0x4c8` | `0x510` | **`+0x48`** |
| `__DATA_CONST.__got` | `0x1c00` | `0x1c48` | **`+0x48`** |
| `__TEXT.__gcc_except_tab` | `0x4e84` | `0x4ecc` | **`+0x48`** |
| `__TEXT.__swift5_builtin` | `0x118` | `0x154` | **`+0x3c`** |
| `__TEXT.__swift5_assocty` | `0x168` | `0x198` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x1460` | `0x1488` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x278` | `0x298` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x10c` | `0x128` | **`+0x1c`** |
| `__DATA_CONST.__objc_classlist` | `0xe08` | `0xe20` | **`+0x18`** |
| `__DATA_CONST.__objc_intobj` | `0x528` | `0x540` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x1e0` | `0x1f8` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x18c` | `0x19c` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x188` | `0x198` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1d4c` | `0x1d58` | **`+0xc`** |
| `__DATA_CONST.__objc_arraydata` | `0x328` | `0x330` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x860` | `0x868` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x2c0` | `0x2c8` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x38` | `0x3c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-5409.0.0.0.0
+5411.0.0.0.0

-  Functions: 12136
-  Symbols:   1518
-  CStrings:  14794
+  Functions: 12341
+  Symbols:   1534
+  CStrings:  14876
Symbols:
+ _$s10Foundation4DateVMn
+ _$s10Foundation4DateVSQAAMc
+ _$s12LockdownMode0aB7ManagerC22threatNotificationDate10Foundation0F0VSgvg
+ _$s20AppManagedFeaturesUI28EnrollmentControllerProviderC19wifiSettingsHandleryycSgvsTj
+ _$s7Combine10PublishersO16RemoveDuplicatesVMn
+ _$s7Combine10PublishersO16RemoveDuplicatesVy_xGAA9PublisherAAMc
+ _$s7Combine9PublisherPAASQ6OutputRpzrlE16removeDuplicatesAA10PublishersO06RemoveE0Vy_xGyF
+ _$sSh10FoundationE19_bridgeToObjectiveCSo5NSSetCyF
+ _$sSo17OS_dispatch_queueC8DispatchE10asyncAfter8deadline7executeyAC0D4TimeV_AC0D8WorkItemCtF
+ _AATermsEntryiCloud
+ _BYSetupAssistantDidCompleteAppleAccountNotification
+ _OBJC_CLASS_$_AAAccountServiceController
+ _OBJC_CLASS_$_AAGenericTermsUIResponse
+ _OBJC_CLASS_$_AAiCloudTermsAgreeRequest
+ _OBJC_CLASS_$_BYChronicleEntry
+ _OBJC_CLASS_$_UILayoutGuide
CStrings:
+ "Account refresh completed without error, terms needed: %{bool}d"
+ "Account refresh failed, falling back to cached terms state: %@"
+ "Already have cached icons"
+ "Apple ID Setup should needs to run checks completed"
+ "Aug  4 2026"
+ "Beginning account refresh..."
+ "Buddy Activate: Partner financing immediate result available - skipping UI"
+ "BuddyLockdownModeManager"
+ "BuddyServicesTermsFlow"
+ "BuddyServicesTermsFlow: servicesTermsProvider does not conform to BuddyCombinedTermsProviderProtocol; falling back to the default combined terms provider"
+ "Combined terms controller is somehow the incorrect type"
+ "Failed to confirm Services terms agreement: %@"
+ "Failed to load combined terms: %{public}@, request URL: %@"
+ "Failed to prefetch icon for %{public}@"
+ "LOCKDOWN_MODE_ON_DETAIL"
+ "LOCKDOWN_MODE_ON_DETAIL_THREAT"
+ "LOCKDOWN_MODE_ON_TITLE"
+ "Missing agreeURL or account, cannot confirm Services terms agreement with the server"
+ "No primary account, nothing to fetch"
+ "No primary account, terms verification not needed"
+ "Posting Apple Account notification"
+ "Prefetched icon for %{public}@, isPlaceholder: %d"
+ "Received response: terms of service update required"
+ "Request unauthorized with preferPassword=true, retrying once with preferPassword=false"
+ "Requesting terms for entries [.entryiCloud], preferPassword = %{bool}d"
+ "Services terms request completed with data length %ld, error (non-nil does not imply failure) = %s"
+ "ServicesTermsFlow needs to run: %{bool}d"
+ "ServicesTermsFlow needs to verify terms: %{bool}d"
+ "Setup.BuddyCameraControlHardwareEligibility"
+ "Setup.LockdownModeManager"
+ "Skipping services terms because this is initial run buddy"
+ "T@\"BYChronicle\",N,&"
+ "T@\"NSMutableDictionary\",&,N,V_expressIconsCache"
+ "T@\"UIViewController\",W,N,V_partnerFinancingVC"
+ "T@?,N,C"
+ "TB,N,V_tappingDeclineShouldPerformForwardNavigation"
+ "VERIFICATON_FAILED"
+ "X-Apple-Show-Terms-Mini-Buddy"
+ "_TtC5Setup26BuddyServicesTermsProvider"
+ "_TtC5Setup37BuddyCameraControlHardwareEligibility"
+ "_expressIconsCache"
+ "_partnerFinancingVC"
+ "_tappingDeclineShouldPerformForwardNavigation"
+ "_userRespondedToCombinedTCsWithAgreement:withSLAVersion:agreeURL:"
+ "aa_isTermsOfServiceUpdateRequired"
+ "aa_needsToVerifyTerms"
+ "accountRefresher"
+ "addLayoutGuide:"
+ "agreeUrl"
+ "agreementRecorder"
+ "animationViewCenterYConstraint"
+ "animationViewCenteringGuide"
+ "animationViewHeightConstraint"
+ "animationViewLockDebounceWorkItem"
+ "checkmark.shield.fill"
+ "com.apple.siri"
+ "convertPoint:toView:"
+ "displayScale"
+ "expressIconsCache"
+ "getCGImageForImageDescriptor:completion:"
+ "hasCommittedConfiguration"
+ "hasCrossedAOrEBoundary"
+ "hasThreatNotification"
+ "immediateResult"
+ "initWithAccount:termsEntries:"
+ "initWithChronicle:deviceConfiguration:"
+ "initWithURLString:account:"
+ "isAnimationViewSizeAndPositionLocked"
+ "isIntroductoryHardware"
+ "lastKnownViewSizeAtLock"
+ "lockdownModeUpgradeVariantNeedsToShow"
+ "osVersionIsAorERelease:"
+ "partnerFinancingVC"
+ "postAppleAccountNotification"
+ "prefetchIconsWithGroup:"
+ "recordUserAgreementWithURL:"
+ "refreshAgainstServer(_:)"
+ "servicesTermsProvider"
+ "setAdditionalHeaders:"
+ "setExpressIconsCache:"
+ "setPartnerFinancingVC:"
+ "setPreferPassword:"
+ "setTappingDeclineShouldPerformForwardNavigation:"
+ "tappingDeclineShouldPerformForwardNavigation"
+ "termsRequestPerformer"
+ "updatePropertiesForAppleAccount:options:completion:"
+ "v16@?0^{CGImage=}8"
+ "\xf0\xf0a"
- "   %s: %ld\n   currentConfiguration: %s"
- "Failed to load combined terms: %@"
- "Jul  9 2026"
- "_TtC5Setup19LockdownModeManager"
- "_userRespondedToCombinedTCsWithAgreement:withSLAVersion:"
- "constraintGreaterThanOrEqualToAnchor:multiplier:"
```
