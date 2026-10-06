## passd

> `/System/Library/PrivateFrameworks/PassKitCore.framework/passd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x60eca8` | `0x6138e4` | **`+0x4c3c`** |
| `__TEXT.__oslogstring` | `0x5ba2b` | `0x5bf5b` | **`+0x530`** |
| `__TEXT.__objc_methname` | `0xa84ac` | `0xa898c` | **`+0x4e0`** |
| `__DATA.__objc_const` | `0x450d8` | `0x45540` | **`+0x468`** |
| `__TEXT.__objc_stubs` | `0x77ea0` | `0x78180` | **`+0x2e0`** |
| `__DATA_CONST.__const` | `0x32a78` | `0x32d48` | **`+0x2d0`** |
| `__DATA_CONST.__cfstring` | `0x35520` | `0x35740` | **`+0x220`** |
| `__TEXT.__cstring` | `0x68bf4` | `0x68d84` | **`+0x190`** |
| `__TEXT.__objc_methlist` | `0x36edc` | `0x3702c` | **`+0x150`** |
| `__DATA.__objc_data` | `0x122a0` | `0x123b8` | **`+0x118`** |
| `__DATA.__data` | `0x7d30` | `0x7e10` | **`+0xe0`** |
| `__TEXT.__swift5_typeref` | `0x4130` | `0x41e6` | **`+0xb6`** |
| `__DATA.__objc_selrefs` | `0x20d90` | `0x20e38` | **`+0xa8`** |
| `__TEXT.__unwind_info` | `0x14570` | `0x14618` | **`+0xa8`** |
| `__TEXT.__swift5_capture` | `0x1b68` | `0x1bf8` | **`+0x90`** |
| `__DATA.__bss` | `0x46b0` | `0x4730` | **`+0x80`** |
| `__TEXT.__const` | `0x5f28` | `0x5f98` | **`+0x70`** |
| `__TEXT.__auth_stubs` | `0x7890` | `0x78f0` | **`+0x60`** |
| `__TEXT.__objc_classname` | `0x8158` | `0x81b8` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x1935` | `0x1995` | **`+0x60`** |
| `__TEXT.__objc_methtype` | `0x14e22` | `0x14e72` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x1a18` | `0x1a64` | **`+0x4c`** |
| `__DATA_CONST.__objc_intobj` | `0x1680` | `0x16c8` | **`+0x48`** |
| `__TEXT.__constg_swiftt` | `0x24cc` | `0x250c` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x2b28` | `0x2b5c` | **`+0x34`** |
| `__DATA_CONST.__auth_got` | `0x3c58` | `0x3c88` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x4890` | `0x48b0` | **`+0x20`** |
| `__DATA_CONST.__objc_arrayobj` | `0x6a8` | `0x690` | **`-0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x1a88` | `0x1aa0` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x90d8` | `0x90f0` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x730` | `0x720` | **`-0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0xfb0` | `0xfc0` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x658` | `0x660` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x108` | `0x110` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x214` | `0x218` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x220` | `0x224` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1686.3.0.0.0
+1689.3.0.0.0

-  Functions: 29686
-  Symbols:   4317
-  CStrings:  36303
+  Functions: 29760
+  Symbols:   4328
+  CStrings:  36379
Symbols:
+ _$s10Foundation4DateV2eeoiySbAC_ACtFZ
+ _$s10Foundation8CalendarV9ComponentO7weekdayyA2EmFWC
+ _OBJC_CLASS_$_PKFlightJourney
+ _PKBestArrivalGateTimeForFlight
+ _PKEngagementAnalyticsEnabledForPass
+ _PKFlightsSortedByDepartureGateTime
+ _PKIdentityTypesSupportingRelevancy
+ _PKPassEngagementAnalyticsDefaultLookbackWindowInDays
+ _PKPassLibraryRelevantInfoBodyText
+ _PKRandomHexStringOfByteCount
+ _swift_cvw_initEnumMetadataSinglePayloadWithLayoutString
+ _swift_cvw_singlePayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_singlePayloadEnumGeneric_getEnumTag
+ _swift_dynamicCastObjCProtocolConditional
- _PKDeviceBacklightActive
- _PKIdentityTypesSupportingPseudoRelevancy
- _PKPassbookUIServiceBacklightActive
CStrings:
+ "-[PDPaymentService removeAllPendingProvisioningsWithCompletion:]"
+ "-[PDPeerPaymentService insertOrUpdateDeviceOriginatedNearbyPeerPaymentTransactionWithIdentifier:secondarySourceDescription:secondarySourceFPANIdentifier:memo:counterpartAppearanceData:completion:]_block_invoke"
+ "@\"PDPassEngagementAnalyticsManager\""
+ "@16@?0@\"PDCandidateRelevantPass\"8"
+ "@48@0:8q16q24q32@40"
+ "CREATE TABLE IF NOT EXISTS pears (pid INTEGER, a TEXT, b INTEGER, c INTEGER, d INTEGER, e INTEGER, f INTEGER, g INTEGER, h TEXT, i INTEGER, j INTEGER, cloud_store_zone_names TEXT, k TEXT, l INTEGER, m TEXT, n TEXT, o TEXT, p INTEGER, transaction_source_pid INTEGER, block_all_account_access INTEGER, current_minimum_os_versions_pid INTEGER, future_minimum_os_versions_pid INTEGER, service_unavailable_period_pid INTEGER, issuer_identifier TEXT, PRIMARY KEY (pid));"
+ "Could not determine recovery payment plan enrollment (error: %@); suppressing past due notification: %@"
+ "Created user notification receipt for account (%@): %@ %@"
+ "Failed to compute upcoming week for %s"
+ "Handle<%@> Failed to start BLE proximity advertisement: no tracker for handle"
+ "Handle<%@> Failed to start CB proximity advertisement: no tracker for handle"
+ "Handle<%@> Failed to start NW proximity advertisement: no tracker for handle"
+ "Handle<%@> Failed to start NW proximity advertisement: secure token generation failed"
+ "Handle<%@> Proximity advertisement requested with type None; nothing to advertise"
+ "Handle<%@> Starting BLE proximity advertisement"
+ "Handle<%@> Starting CB proximity advertisement"
+ "Handle<%@> Starting NW proximity advertisement with high-entropy token (length: %{private}lu)"
+ "Migrating database from user_version 26062 to 26063"
+ "Notifications blocked for account %s, skipping"
+ "PDFlightManager: Flight %@ missing arrival time zone"
+ "PDFlightManager: Flight %@ missing departure time zone"
+ "PDPassEngagementAnalyticsManager"
+ "PDRelevantPassPresentationOptions"
+ "PDWatchIssuerProvisioningSupport"
+ "Pass composition analytics"
+ "Relevancy: no flights matching expected criteria found."
+ "Removing upcoming transactions notification: %s"
+ "Scheduled upcoming transactions notification: %s, chargeCount: %ld, paymentCount: %ld, date: %s"
+ "T@\"NSArray\",C,N,V_excludedPassUniqueIdentifiers"
+ "T@\"NSSet\",C,N,V_passSortingStates"
+ "T@\"NSString\",R,C,N,V_relevantText"
+ "Too little lead to schedule an upcoming transactions notification for %s; skipping this cycle"
+ "Tq,N,V_bodyTextSource"
+ "Tq,R,N,V_bodyTextSource"
+ "Tq,R,N,V_iconSource"
+ "Tq,R,N,V_titleTextSource"
+ "Upcoming transactions notification %s preserved (up to date, or fires too soon to re-register safely)"
+ "Within the Sunday notification fire window; leaving the scheduled notification untouched"
+ "_applicableDateByUniqueID"
+ "_augmentCandidatePassWithIdentityRelevancy:"
+ "_bodyTextSource"
+ "_cachedIdentityRelevantDate"
+ "_didComputeIdentityRelevantDate"
+ "_excludedPassUniqueIdentifiers"
+ "_identityRelevantDateFromCurrentBoardingPasses"
+ "_migrateFrom26062To26063:context:"
+ "_passEngagementAnalyticsManager"
+ "_passSortingStates"
+ "_presentationOptionsByUniqueID"
+ "_registerScheduledActivityIfNeeded"
+ "_relevantPassFactories"
+ "_resolvedPaymentCandidates"
+ "addCandidate:forDate:relevantText:"
+ "air"
+ "boat"
+ "bodyTextSource"
+ "canAddSecureElementPass: called while Wallet is restricted"
+ "canAddSecureElementPassWithConfiguration: synchronous variant not supported on target device; use the asynchronous check."
+ "canAddSecureElementPassWithConfiguration:completion:"
+ "candidateIdentityPasses"
+ "conference"
+ "convention"
+ "defaultMaximumLayover"
+ "excludedPassUniqueIdentifiers"
+ "fieldDetect"
+ "flightJourneysFromFlights:maximumLayover:"
+ "flightsFromPassesOfStyle:"
+ "initWithIconSource:titleTextSource:bodyTextSource:relevantText:"
+ "initWithWebService:cloudStoreCoordinator:carKeyRequirementsChecker:pushProvisioningManager:"
+ "insertOrUpdateDeviceOriginatedNearbyPeerPaymentMemo:secondarySourceDescription:secondarySourceFPANIdentifier:counterpartImageDataIdentifier:forTransactionWithServiceIdentifier:completion:"
+ "insertOrUpdateDeviceOriginatedNearbyPeerPaymentTransactionWithIdentifier:secondarySourceDescription:secondarySourceFPANIdentifier:memo:counterpartAppearanceData:completion:"
+ "insertPass:forDate:presentationOptions:"
+ "isWatchIssuerAppProvisioningSupported"
+ "issuer_identifier"
+ "issuer_identifier TEXT"
+ "livePerformance"
+ "movie"
+ "nfcFieldExit"
+ "originLeg"
+ "pass:fieldDetect"
+ "pass:nfcFieldExit"
+ "passDeleted:"
+ "passSortingStates"
+ "posterEventTicket"
+ "predicateForPassAnnotationStatesInExpiredSectionAutomatically"
+ "predicateForPassSortingStates:"
+ "predicateForPersonalizedPaymentApplications"
+ "presentationOptionsForCandidate:"
+ "removeAllPendingProvisionings"
+ "removeAllPendingProvisioningsWithCompletion:"
+ "reportPassAdded:source:hasOtherPasses:addedAnyPassesDuringLookback:lookbackWindowInDays:"
+ "reportPassComposition"
+ "reportPassCompositionWithSEPassCount:barcodePassCount:"
+ "reportPassCounts"
+ "reportPassDeleted:"
+ "semanticBoardingPass"
+ "setBodyTextSource:"
+ "setExcludedPassUniqueIdentifiers:"
+ "setPassSortingStates:"
+ "socialGathering"
+ "sports"
+ "v64@0:8@\"NSString\"16@\"NSString\"24@\"NSString\"32@\"NSString\"40@\"PKPeerPaymentProfileAppearanceData\"48@?<v@?B>56"
+ "workshop"
+ "\xf0\xe1"
+ "\xf0\xf01"
- "-[PDPeerPaymentService insertOrUpdateDeviceOriginatedNearbyPeerPaymentTransactionWithIdentifier:memo:counterpartAppearanceData:completion:]_block_invoke"
- "CREATE TABLE IF NOT EXISTS pears (pid INTEGER, a TEXT, b INTEGER, c INTEGER, d INTEGER, e INTEGER, f INTEGER, g INTEGER, h TEXT, i INTEGER, j INTEGER, cloud_store_zone_names TEXT, k TEXT, l INTEGER, m TEXT, n TEXT, o TEXT, p INTEGER, transaction_source_pid INTEGER, block_all_account_access INTEGER, current_minimum_os_versions_pid INTEGER, future_minimum_os_versions_pid INTEGER, service_unavailable_period_pid INTEGER, PRIMARY KEY (pid));"
- "Created user notification receipt: %@ %@"
- "Failed to compute upcoming week range"
- "Failed to compute year/week for upcoming week"
- "Relevancy: No associated flights found for %lu boarding pass%@ fitting expected conditions"
- "Scheduled upcoming transactions notification: %s, date: %s"
- "T@\"PDCarKeyRequirementsChecker\",&,N,V_carKeyRequirementsChecker"
- "_isWatchIssuerAppProvisioningSupported"
- "_updateWithPseudoRelevantPassesBasedOnCatalog:"
- "addCandidateForPseudoRelevancy:withRelevantText:"
- "canAddCarKeyPassWithConfiguration: synchronous not supported."
- "canAddClassicApplePayCredentialWithConfiguration:completion:"
- "canAddPushablePassWithConfiguration:completion:"
- "canAddSecureElementPassWithConfiguration: called while Wallet is restricted"
- "candidatePassesSupportingPseudoRelevancy"
- "es"
- "initWithWebService:cloudStoreCoordinator:"
- "insertOrUpdateDeviceOriginatedNearbyPeerPaymentMemo:counterpartImageDataIdentifier:forTransactionWithServiceIdentifier:completion:"
- "insertOrUpdateDeviceOriginatedNearbyPeerPaymentTransactionWithIdentifier:memo:counterpartAppearanceData:completion:"
- "insertPassForPseudoRelevancy:withRelevantText:"
- "numberWithUnsignedChar:"
- "q24@?0@\"PKFlight\"8@\"PKFlight\"16"
- "setCarKeyRequirementsChecker:"
- "usingSynchronousProxy:canAddCarKeyPassWithConfiguration:completion:"
- "v36@0:8B16@\"PKAddCarKeyPassConfiguration\"20@?<v@?B@\"PKCarUnlockSupportedTerminal\"@\"NSError\">28"
- "v48@0:8@\"NSString\"16@\"NSString\"24@\"PKPeerPaymentProfileAppearanceData\"32@?<v@?B>40"
- "\xf0\xd1"
- "\xf0\xf0A"
```
