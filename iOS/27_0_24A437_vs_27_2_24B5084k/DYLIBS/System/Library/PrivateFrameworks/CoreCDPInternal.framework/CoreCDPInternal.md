## CoreCDPInternal

> `/System/Library/PrivateFrameworks/CoreCDPInternal.framework/CoreCDPInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8dda4` | `0x8f7e8` | **`+0x1a44`** |
| `__TEXT.__oslogstring` | `0x14a9e` | `0x1503e` | **`+0x5a0`** |
| `__TEXT.__cstring` | `0xe0c5` | `0xe5b5` | **`+0x4f0`** |
| `__AUTH_CONST.__cfstring` | `0x9520` | `0x98a0` | **`+0x380`** |
| `__TEXT.__objc_methlist` | `0x568c` | `0x5774` | **`+0xe8`** |
| `__DATA_CONST.__objc_selrefs` | `0x3908` | `0x39b8` | **`+0xb0`** |
| `__TEXT.__unwind_info` | `0x1e10` | `0x1e70` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0x100b0` | `0x100f0` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x25c8` | `0x2608` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x10f0` | `0x1128` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0x960` | `0x968` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x3b0` | `0x3b8` | **`+0x8`** |

### Other Changes

```diff

-447.0.0.0.0
+448.125.5.1.0

+  - /usr/lib/swift/libswiftAVFoundation.dylib

+  - /usr/lib/swift/libswiftCoreMIDI.dylib

+  - /usr/lib/swift/libswiftIntents.dylib

-  Functions: 3159
-  Symbols:   4153
-  CStrings:  2809
+  Functions: 3196
+  Symbols:   4191
+  CStrings:  2855
Symbols:
+ +[CDPDPCSController _flagsForValidateTelemetry:]
+ +[CDPDPCSController passwordVersionsWereComparedForValidateTelemetry:]
+ +[CDPDPCSController primaryAttemptsRemainingForValidateTelemetry:]
+ +[CDPDPCSController recordGenerationIsAheadOfAccountForValidateTelemetry:]
+ +[CDPDPCSController wrappingKeyNeededRepairForValidateTelemetry:]
+ +[CDPDPCSController wrappingKeyWasRebuiltForValidateTelemetry:]
+ +[CDPDXPCListener _isAppleBinaryOrInternalBuildWithCodeSignFlags:isInternalBuild:]
+ -[CDPContext(Daemon) hasConfirmedPDPIneligibility]
+ -[CDPDPDPRecoveryController retirePDPFollowUpIfAccountConfirmedIneligible]
+ -[CDPDStateMachine _attemptLegacyIntermissionFallbackWithCompletion:]
+ -[CDPDStateMachine _attemptNativeIntermissionSalvageAfterSetupError:completion:]
+ -[CDPDStateMachine _attemptPreOctagonPDPSetupWithCompletion:continuation:]
+ -[CDPDStateMachine _finishSignInWithSecretTeardownShouldComplete:cloudDataProtectionEnabled:error:completion:]
+ -[CDPDStateMachine _makeDeferredSOSStateMachineWithContext:]
+ -[CDPDStateMachine _markRepairPairReported]
+ -[CDPDStateMachine _sendDBRDetectionEventsWithDetails:healthState:]
+ -[CDPDStateMachine _sendDBRRepairEntryEventWithDetails:validationError:includeRepairContext:]
+ -[CDPDXPCListener _isAppleBinaryOrInternalBuildConnection:]
+ GCC_except_table120
+ GCC_except_table34
+ GCC_except_table48
+ _OBJC_IVAR_$_CDPDStateMachine._pdpDetectionEventsAlreadySent
+ _OBJC_IVAR_$_CDPDStateMachine._pdpRepairPairAlreadySent
+ _SecTaskGetCodeSignStatus
+ __OBJC_$_CLASS_METHODS_CDPDPCSController
+ ___110-[CDPDStateMachine _finishSignInWithSecretTeardownShouldComplete:cloudDataProtectionEnabled:error:completion:]_block_invoke
+ ___69-[CDPDStateMachine _attemptLegacyIntermissionFallbackWithCompletion:]_block_invoke
+ ___74-[CDPDStateMachine _attemptPreOctagonPDPSetupWithCompletion:continuation:]_block_invoke
+ ___80-[CDPDStateMachine _attemptNativeIntermissionSalvageAfterSetupError:completion:]_block_invoke
+ ___block_descriptor_48_e8_32s40bs_e37_v32?0Q8"NSDictionary"16"NSError"24ls32l8s40l8
+ ___block_descriptor_57_e8_32s40s48bs_e20_v20?0"NSError"8B16ls48l8s32l8s40l8
+ ___block_descriptor_64_e8_32s40s48bs56bs_e20_v20?0"NSError"8B16ls32l8s40l8s48l8s56l8
+ __swift_FORCE_LOAD_$_swiftAVFoundation
+ __swift_FORCE_LOAD_$_swiftAVFoundation_$_CoreCDPInternal
+ __swift_FORCE_LOAD_$_swiftCoreMIDI
+ __swift_FORCE_LOAD_$_swiftCoreMIDI_$_CoreCDPInternal
+ __swift_FORCE_LOAD_$_swiftIntents
+ __swift_FORCE_LOAD_$_swiftIntents_$_CoreCDPInternal
+ _kCDPAnalyticsPDPRecordGenerationAheadEvent
+ _kCDPAnalyticsPDPRecordGenerationCheckSkippedEvent
+ _kCDPAnalyticsPDPWrappingKeyRepairEvent
+ _kPCSDBRTelemetryFlags
+ _kPCSDBRTelemetryLocalPasswordVersion
+ _kPCSDBRTelemetryPrimaryAttemptsRemaining
+ _kPCSDBRTelemetryRecordPasswordVersion
- GCC_except_table121
- GCC_except_table35
- GCC_except_table47
- ___70-[CDPDClientHandler setUserVisibleKeychainSyncEnabled:withCompletion:]_block_invoke_2
- ___77-[CDPDClientHandler removeNonViewAwarePeersFromCircleWithContext:completion:]_block_invoke_2
- ___block_descriptor_48_e8_32s40bs_e37_v32?0Q8"NSDictionary"16"NSError"24ls40l8s32l8
- ___block_descriptor_56_e8_32s40s48bs_e20_v20?0"NSError"8B16ls32l8s40l8s48l8
CStrings:
+ "CDPDStateMachine: Active PDP user PDP fallback failed — blocking sign-in directly (bypassing localCompletion head)"
+ "CDPDStateMachine: Attempting native intermission for active DBR user"
+ "CDPDStateMachine: Attempting post-Octagon PDP setup"
+ "CDPDStateMachine: Intermission ineligible (non-active PDP user): %@"
+ "CDPDStateMachine: Native intermission succeeded, processing temporary stingray record"
+ "CDPDStateMachine: Post-Octagon PDP fallback should not be attempted on HomePod"
+ "CDPDStateMachine: Skipping post-Octagon PDP setup due to forced Manatee reset"
+ "CDPDStateMachine: TTSU recovery, bypassing password-based PDP setup; routing to native intermission"
+ "CDPDStateMachine: post-Octagon setupPDPState did %@ set up with error=%@"
+ "Denying hasLocalSecret: missing cdp.utility entitlement."
+ "Denying isICDPEnabledForDSID: missing cdp.utility entitlement."
+ "Denying isUserVisibleKeychainSyncEnabled: missing cdp.statemachine entitlement."
+ "Denying new connection %@: caller is not an Apple-signed binary or an internal build."
+ "Denying removeNonViewAwarePeersFromCircle: missing cdp.statemachine entitlement."
+ "Denying setUserVisibleKeychainSyncEnabled: missing cdp.statemachine entitlement."
+ "Denying synchronizeUserVisibleKeychainSyncEligibility: missing cdp.statemachine entitlement."
+ "Denying verifyRecoveryKeyObservingSystemsHaveMatchingState: missing cdp.recoverykey entitlement."
+ "PDP: Account is ineligible for PDP, retiring the PDP repair CFU it can no longer satisfy"
+ "PDP: Cannot attribute the PDP repair CFU to this account, leaving it in place"
+ "RUIHTTPRequestErrorDomain"
+ "ak-button"
+ "com.apple.appleaccounttransparency.cachedEventsFetched"
+ "com.apple.appleaccounttransparency.metadataGenerated"
+ "com.apple.appleaccounttransparency.metadataGenerated.hook"
+ "com.apple.appleaccounttransparency.pushReceived"
+ "com.apple.appleaccounttransparency.syncTriggered"
+ "com.apple.authkit.TDIDTrustLoss"
+ "com.apple.authkit.TDLChangePushReceived"
+ "com.apple.authkit.TDLTDIDAvailability"
+ "com.apple.authkit.signoutEnd"
+ "com.apple.authkit.signoutStart"
+ "com.apple.remoteUI.loadURLComplete"
+ "com.apple.remoteui.appleid_settings_account_manage_security"
+ "com.apple.remoteui.appleid_settings_account_manage_security_password"
+ "com.apple.remoteui.appleid_settings_account_manage_security_password_put"
+ "com.apple.remoteui.appleid_settings_account_manage_security_password_signout_put"
+ "com.apple.remoteui.auth"
+ "com.apple.remoteui.auth_verify_passcode"
+ "com.apple.remoteui.auth_verify_phone_1_put"
+ "com.apple.remoteui.auth_verify_phone_securitycode"
+ "com.apple.security.RKSponsorSelection"
+ "com.apple.security.TLKProofInvalid"
+ "com.apple.security.anyPotentialRKSponsorsWithFlagSet"
+ "com.apple.security.joinWithCircleReset"
+ "com.apple.security.prepareTDIDPresence"
+ "com.apple.security.recoverRKTLKShares.fetchRKTLKSharesForRecovery"
+ "com.apple.security.recoverRKTLKShares.recoveredRKTLKShares"
+ "com.apple.security.tdlTDIDDuplicates"
+ "com.apple.security.tdlTDIDReappearance"
+ "com.apple.security.tdlTDIDStability"
+ "com.apple.security.vouchWithRecoveryKeyOperation"
- "CDPDStateMachine: PDP fallback (native intermission) should not be attempted on HomePod"
- "com.apple.authkit.StableIDAvailability"
- "com.apple.authkit.TDIDAvailability"
- "com.apple.authkit.TDIDAvailability.signin"
- "com.apple.authkit.TDIDAvailability.upgrade"
```
