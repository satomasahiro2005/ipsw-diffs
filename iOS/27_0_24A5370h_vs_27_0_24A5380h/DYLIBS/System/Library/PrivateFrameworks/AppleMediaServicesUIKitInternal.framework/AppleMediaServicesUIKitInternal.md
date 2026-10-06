## AppleMediaServicesUIKitInternal

> `/System/Library/PrivateFrameworks/AppleMediaServicesUIKitInternal.framework/AppleMediaServicesUIKitInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb5b50` | `0xd9564` | **`+0x23a14`** |
| `__TEXT.__eh_frame` | `0x32cc` | `0x4554` | **`+0x1288`** |
| `__TEXT.__oslogstring` | `0x13e4` | `0x2134` | **`+0xd50`** |
| `__TEXT.__const` | `0x79a4` | `0x85f4` | **`+0xc50`** |
| `__TEXT.__swift5_typeref` | `0xbc3e` | `0xc85e` | **`+0xc20`** |
| `__AUTH_CONST.__const` | `0x3848` | `0x4058` | **`+0x810`** |
| `__TEXT.__unwind_info` | `0x2080` | `0x2758` | **`+0x6d8`** |
| `__DATA.__bss` | `0x26b0` | `0x2d70` | **`+0x6c0`** |
| `__DATA.__data` | `0x18a8` | `0x1cd8` | **`+0x430`** |
| `__TEXT.__constg_swiftt` | `0x2c7c` | `0x3000` | **`+0x384`** |
| `__TEXT.__swift5_fieldmd` | `0x1a68` | `0x1de0` | **`+0x378`** |
| `__TEXT.__swift5_reflstr` | `0x165b` | `0x19ab` | **`+0x350`** |
| `__AUTH.__data` | `0xce8` | `0xfd8` | **`+0x2f0`** |
| `__TEXT.__cstring` | `0x19c2` | `0x1c22` | **`+0x260`** |
| `__TEXT.__swift5_capture` | `0xbe4` | `0xe3c` | **`+0x258`** |
| `__AUTH_CONST.__objc_const` | `0x1100` | `0x12b0` | **`+0x1b0`** |
| `__AUTH_CONST.__auth_got` | `0x1ab0` | `0x1c40` | **`+0x190`** |
| `__DATA_CONST.__got` | `0xbb8` | `0xc80` | **`+0xc8`** |
| `__TEXT.__swift_as_cont` | `0x2a0` | `0x350` | **`+0xb0`** |
| `__DATA_DIRTY.__data` | `0x2880` | `0x2800` | **`-0x80`** |
| `__TEXT.__swift5_assocty` | `0x938` | `0x9b0` | **`+0x78`** |
| `__DATA_CONST.__objc_selrefs` | `0x500` | `0x568` | **`+0x68`** |
| `__AUTH.__objc_data` | `0x118` | `0x168` | **`+0x50`** |
| `__TEXT.__swift_as_ret` | `0x12c` | `0x17c` | **`+0x50`** |
| `__TEXT.__swift_as_entry` | `0xbc` | `0x100` | **`+0x44`** |
| `__DATA.__common` | `0x160` | `0x1a0` | **`+0x40`** |
| `__TEXT.__swift5_proto` | `0x1e0` | `0x210` | **`+0x30`** |
| `__TEXT.__swift5_types` | `0x1d0` | `0x1f4` | **`+0x24`** |
| `__DATA_CONST.__const` | `0xc0` | `0xe0` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x80` | `0x88` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x2f8` | `0x2f0` | **`-0x8`** |

### Other Changes

```diff

-2.0.21.0.0
+2.0.23.0.0

-  Functions: 2968
-  Symbols:   251
-  CStrings:  232
+  Functions: 3467
+  Symbols:   260
+  CStrings:  290
Symbols:
+ _NSUbiquitousKeyValueStoreDidChangeExternallyNotification
+ _OBJC_CLASS_$_AKAccountManager
+ _OBJC_CLASS_$_AKAppleIDAuthenticationController
+ _OBJC_CLASS_$_NSDateFormatter
+ _OBJC_CLASS_$_NSNotificationCenter
+ _objc_retain_x27
+ _swift_bridgeObjectRetain_n
+ _swift_coroFrameAlloc
+ _swift_isEscapingClosureAtFileLocation
+ _swift_release_x3
+ _swift_task_getMainExecutor
- _swift_getObjCClassFromMetadata
- _swift_willThrowTypedImpl
CStrings:
+ "AMSUIKit.SignificantChange."
+ "AgeProvider.age: computed age = %ld"
+ "AgeProvider.age: failed to compute year-delta from birthday"
+ "AgeProvider.age: fetched birthday = %{private}s"
+ "AgeProvider.age: starting AuthKit birthday fetch"
+ "AgeProvider.ageOfMajority: jurisdictional majority = %ld"
+ "AgeProvider.ageOfMajority: no primary Apple account, defaulting to %ld"
+ "AgeProvider: AKAppleIDAuthenticationController() returned nil"
+ "AgeProvider: calling AKAppleIDAuthenticationController.fetchBirthday"
+ "AgeProvider: fetchBirthday callback error: %s"
+ "AgeProvider: fetchBirthday callback parsed date OK"
+ "AgeProvider: fetchBirthday callback returned no error but parts could not be assembled (birthday=%{private}s, birthmonth=%{private}s)"
+ "AgeProvider: fetching birthday from AuthKit"
+ "AgeProvider: no birth year for account"
+ "AgeProvider: no primary AuthKit account"
+ "AgeProvider: no primary altDSID"
+ "AgeProvider: resolved altDSID"
+ "AgeProvider: resolved birthYear = %{private}@"
+ "AgeProvider: resolved primary AuthKit account"
+ "AppBlockingModifier: .adultRequiresAck → showSignificantUpdateAcknowledgment"
+ "AppBlockingModifier: .minorRequiresConsent → cover will show via shouldBlock"
+ "AppBlockingModifier: .notApplicable → markAsHandled"
+ "AppBlockingModifier: adult ack succeeded → markAsHandled"
+ "AppBlockingModifier: every declared change already handled; skipping resolver"
+ "AppBlockingModifier: resolving decision for %ld/%ld still-pending change(s)"
+ "AppleMediaServicesUIKitInternal/SignificantChangeBlocking.swift"
+ "AppleMediaServicesUIKitInternal/SignificantChangeStore.swift"
+ "Approval Unavailable"
+ "CFBundleShortVersionString"
+ "ComplianceResolver: AuthKit branch — fetching age + ageOfMajority"
+ "ComplianceResolver: AuthKit isMinor=%{bool}d (age=%ld threshold=%ld)"
+ "ComplianceResolver: age check failed: %s"
+ "ComplianceResolver: failing closed to %s"
+ "ComplianceResolver: features parental=%{bool}d adult=%{bool}d"
+ "ComplianceResolver: fetching requiredRegulatoryFeatures"
+ "ComplianceResolver: final decision → %s"
+ "ComplianceResolver: no relevant feature → .notApplicable"
+ "ComplianceResolver: requiredRegulatoryFeatures failed: %s — failing closed to .minorRequiresConsent"
+ "ComplianceResolver: using test seam override → %s"
+ "Could not request approval at this time. Please try again later."
+ "DeclaredAgeRangeAction"
+ "Duplicate values for key: '"
+ "Failed to load jetpack: "
+ "Fatal error"
+ "FeatureBlockingModifier(%{public}s): .adultRequiresAck → showSignificantUpdateAcknowledgment"
+ "FeatureBlockingModifier(%{public}s): .minorRequiresConsent → presenting cover sheet"
+ "FeatureBlockingModifier(%{public}s): .notApplicable → markAsHandled, dismissing"
+ "FeatureBlockingModifier(%{public}s): adult ack already in flight — skipping re-dispatch"
+ "FeatureBlockingModifier(%{public}s): adult ack succeeded → markAsHandled"
+ "FeatureBlockingModifier(%{public}s): decision = %s"
+ "FeatureBlockingModifier(%{public}s): resolving decision"
+ "Incorrect actor executor assumption; Expected same executor as "
+ "Optional<SignificantChangeStore>"
+ "OriginalAppVersion"
+ "PendingApprovals"
+ "SignificantChangeBlockingHostView ask failed: %s"
+ "SignificantUpdateAction"
+ "Swift/NativeDictionary.swift"
+ "View.task @ AppleMediaServicesUIKitInternal/AMSUIKitStoreAccountProfileButton.swift:"
+ "View.task @ AppleMediaServicesUIKitInternal/SignificantChangeBlocking.swift:"
+ "significantChangeAppBlocking adult-acknowledgment failed: %s. Leaving changes unhandled; will retry next launch."
+ "significantChangeAppBlocking applied without a SignificantChangeStore in the environment. Apply .significantChangeStore(_:) above this view. Blocking is disabled."
+ "significantChangeFeatureBlocking adult-acknowledgment failed: %s. Leaving change unhandled; will retry next presentation."
+ "significantChangeFeatureBlocking applied without a SignificantChangeStore in the environment. Apply .significantChangeStore(_:) above this view. Blocking is disabled."
+ "waitUntilReady()"
- "Failed to create bundle from "
- "Failed to load Jetpack: "
- "Failed to load jetpack resource bundle."
- "Failed to load jetpack with error: "
- "Jetpack missing from app bundle at: "
- "Using amsuikit-account-hub.jetpack loaded from bundle: "
- "amsuikit-account-hub"
```
