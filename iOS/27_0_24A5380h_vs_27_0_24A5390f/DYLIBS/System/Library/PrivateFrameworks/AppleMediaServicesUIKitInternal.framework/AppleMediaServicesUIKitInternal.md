## AppleMediaServicesUIKitInternal

> `/System/Library/PrivateFrameworks/AppleMediaServicesUIKitInternal.framework/AppleMediaServicesUIKitInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd9564` | `0xe4b68` | **`+0xb604`** |
| `__DATA.__bss` | `0x2d70` | `0x40b0` | **`+0x1340`** |
| `__TEXT.__const` | `0x85f4` | `0x9374` | **`+0xd80`** |
| `__TEXT.__swift5_typeref` | `0xc85e` | `0xd35e` | **`+0xb00`** |
| `__AUTH_CONST.__const` | `0x4058` | `0x44e8` | **`+0x490`** |
| `__TEXT.__oslogstring` | `0x2134` | `0x1e24` | **`-0x310`** |
| `__DATA_DIRTY.__bss` | `0x1bb0` | `0x1eb0` | **`+0x300`** |
| `__DATA_DIRTY.__data` | `0x2800` | `0x2a60` | **`+0x260`** |
| `__TEXT.__constg_swiftt` | `0x3000` | `0x325c` | **`+0x25c`** |
| `__DATA.__data` | `0x1cd8` | `0x1ef8` | **`+0x220`** |
| `__TEXT.__unwind_info` | `0x2758` | `0x2968` | **`+0x210`** |
| `__TEXT.__swift5_fieldmd` | `0x1de0` | `0x1fe0` | **`+0x200`** |
| `__AUTH_CONST.__auth_got` | `0x1c40` | `0x1d58` | **`+0x118`** |
| `__TEXT.__swift5_reflstr` | `0x19ab` | `0x1abb` | **`+0x110`** |
| `__TEXT.__cstring` | `0x1c22` | `0x1d12` | **`+0xf0`** |
| `__TEXT.__swift5_capture` | `0xe3c` | `0xefc` | **`+0xc0`** |
| `__TEXT.__swift5_proto` | `0x210` | `0x2c0` | **`+0xb0`** |
| `__DATA_CONST.__got` | `0xc80` | `0xd18` | **`+0x98`** |
| `__AUTH.__data` | `0xfd8` | `0xf68` | **`-0x70`** |
| `__TEXT.__swift5_assocty` | `0x9b0` | `0xa10` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x568` | `0x528` | **`-0x40`** |
| `__TEXT.__swift5_types` | `0x1f4` | `0x224` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x12b0` | `0x12d0` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0xb4` | `0xc8` | **`+0x14`** |
| `__TEXT.__eh_frame` | `0x4554` | `0x4564` | **`+0x10`** |
| `__DATA.__common` | `0x1a0` | `0x198` | **`-0x8`** |
| `__DATA_DIRTY.__common` | `0x130` | `0x138` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x350` | `0x348` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x100` | `0x108` | **`+0x8`** |

### Other Changes

```diff

-2.0.23.0.0
+2.0.26.0.0

-  Functions: 3467
-  Symbols:   260
-  CStrings:  290
+  Functions: 3706
+  Symbols:   265
+  CStrings:  281
Symbols:
+ _AMSErrorDomain
+ _OBJC_CLASS_$_AMSAuthenticateTask
+ _OBJC_CLASS_$_AMSProcessInfo
+ _objc_retain_x1
+ _swift_cvw_initEnumMetadataSinglePayloadWithLayoutString
+ _swift_cvw_singlePayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_singlePayloadEnumGeneric_getEnumTag
+ _swift_retain_x9
+ _swift_unknownObjectRetain_n
- _OBJC_CLASS_$_AKAccountManager
- _OBJC_CLASS_$_AKAppleIDAuthenticationController
- _OBJC_CLASS_$_NSDateFormatter
- _objc_retain_x27
CStrings:
+ "AMS.UIKit.AccountHub.AccountButton.SignIn"
+ "AMS.UIKit.AccountHub.SignIn.Disabled"
+ "ComplianceResolver: userAge SPI isMinor=%{bool}d (age=%ld approvalAge=%ld)"
+ "ComplianceResolver: userAge unavailable — falling back to \\.requestAgeRange"
+ "FeatureBlockingModifier(%{public}s): .minorRequiresConsent → presenting cover"
+ "Invalid number of keys found, expected one."
+ "Running silent AMSAuthenticateTask inline"
+ "Something went wrong"
+ "We couldn't show the update notification. Please try again."
+ "handleAuthenticateRequest: %@"
+ "handleDialogRequest: %@"
+ "listenForAskResponses: received approval — questionID: %s"
+ "listenForAskResponses: received non-approval (declined) — questionID: %s; clearing pending entry"
+ "persistPendingApprovals: failed to encode pending-approval state; leaving stored value unchanged"
+ "restorePendingApprovals: stored value is not decodable; removing stale entry (pending approvals expire in 24h)"
+ "significantChangeAppBlocking adult-acknowledgment failed: %s. Surfacing retry alert."
+ "significantChangeFeatureBlocking adult-acknowledgment failed: %s. Surfacing retry alert."
- "AMSUIKitAccountHubWebViewModel creating webModel"
- "AgeProvider.age: computed age = %ld"
- "AgeProvider.age: failed to compute year-delta from birthday"
- "AgeProvider.age: fetched birthday = %{private}s"
- "AgeProvider.age: starting AuthKit birthday fetch"
- "AgeProvider.ageOfMajority: jurisdictional majority = %ld"
- "AgeProvider.ageOfMajority: no primary Apple account, defaulting to %ld"
- "AgeProvider: AKAppleIDAuthenticationController() returned nil"
- "AgeProvider: calling AKAppleIDAuthenticationController.fetchBirthday"
- "AgeProvider: fetchBirthday callback error: %s"
- "AgeProvider: fetchBirthday callback parsed date OK"
- "AgeProvider: fetchBirthday callback returned no error but parts could not be assembled (birthday=%{private}s, birthmonth=%{private}s)"
- "AgeProvider: fetching birthday from AuthKit"
- "AgeProvider: no birth year for account"
- "AgeProvider: no primary AuthKit account"
- "AgeProvider: no primary altDSID"
- "AgeProvider: resolved altDSID"
- "AgeProvider: resolved birthYear = %{private}@"
- "AgeProvider: resolved primary AuthKit account"
- "ComplianceResolver: AuthKit branch — fetching age + ageOfMajority"
- "ComplianceResolver: AuthKit isMinor=%{bool}d (age=%ld threshold=%ld)"
- "FeatureBlockingModifier(%{public}s): .minorRequiresConsent → presenting cover sheet"
- "handleAuthenticateRequest called"
- "handleDialogRequest called"
- "significantChangeAppBlocking adult-acknowledgment failed: %s. Leaving changes unhandled; will retry next launch."
- "significantChangeFeatureBlocking adult-acknowledgment failed: %s. Leaving change unhandled; will retry next presentation."
```
