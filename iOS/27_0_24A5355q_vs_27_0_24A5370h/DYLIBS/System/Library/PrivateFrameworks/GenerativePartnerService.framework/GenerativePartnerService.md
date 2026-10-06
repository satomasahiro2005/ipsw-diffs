## GenerativePartnerService

> `/System/Library/PrivateFrameworks/GenerativePartnerService.framework/GenerativePartnerService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7bf78` | `0x872b8` | **`+0xb340`** |
| `__TEXT.__oslogstring` | `0x357d` | `0x3f4d` | **`+0x9d0`** |
| `__TEXT.__eh_frame` | `0x4220` | `0x47e0` | **`+0x5c0`** |
| `__TEXT.__const` | `0x45b8` | `0x48a8` | **`+0x2f0`** |
| `__TEXT.__unwind_info` | `0x2178` | `0x23c8` | **`+0x250`** |
| `__TEXT.__cstring` | `0x1afb` | `0x1cfb` | **`+0x200`** |
| `__TEXT.__swift5_reflstr` | `0x10c1` | `0x12c1` | **`+0x200`** |
| `__AUTH_CONST.__const` | `0x5cc0` | `0x5e48` | **`+0x188`** |
| `__AUTH_CONST.__auth_got` | `0x1310` | `0x1410` | **`+0x100`** |
| `__TEXT.__swift5_fieldmd` | `0x1468` | `0x152c` | **`+0xc4`** |
| `__TEXT.__swift5_typeref` | `0x1331` | `0x13ed` | **`+0xbc`** |
| `__DATA_DIRTY.__data` | `0xd08` | `0xc60` | **`-0xa8`** |
| `__TEXT.__constg_swiftt` | `0x1420` | `0x14c0` | **`+0xa0`** |
| `__AUTH.__data` | `0xc50` | `0xce0` | **`+0x90`** |
| `__DATA.__bss` | `0x4720` | `0x46a0` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `0xc00` | `0xb80` | **`-0x80`** |
| `__DATA.__data` | `0x988` | `0x9e8` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x1c0` | `0x210` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `0x300` | `0x34c` | **`+0x4c`** |
| `__AUTH_CONST.__objc_const` | `0xfa8` | `0xfe8` | **`+0x40`** |
| `__DATA.__common` | `0xf0` | `0x128` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x338` | `0x370` | **`+0x38`** |
| `__TEXT.__swift5_capture` | `0x1190` | `0x11b4` | **`+0x24`** |
| `__TEXT.__swift_as_entry` | `0x170` | `0x194` | **`+0x24`** |
| `__TEXT.__swift_as_ret` | `0x17c` | `0x1a0` | **`+0x24`** |
| `__DATA_CONST.__got` | `0x790` | `0x7a0` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x1a4` | `0x1b0` | **`+0xc`** |
| `__TEXT.__swift5_protos` | `0xc` | `0x14` | **`+0x8`** |

### Other Changes

```diff

-279.0.15.0.0
+284.0.7.0.0

+  - /System/Library/PrivateFrameworks/Anvil.framework/Anvil

-  - /System/Library/PrivateFrameworks/FeatureFlags.framework/FeatureFlags

+  - /System/Library/PrivateFrameworks/ManagedConfiguration.framework/ManagedConfiguration

-  Functions: 3887
-  Symbols:   231
-  CStrings:  393
+  Functions: 4111
+  Symbols:   235
+  CStrings:  434
Symbols:
+ _OBJC_CLASS_$_MCProfileConnection
+ _OBJC_CLASS_$_NSDictionary
+ _SecTaskCopyValuesForEntitlements
+ _objc_retain_x24
+ _os_variant_has_internal_ui
- _TCCAccessPreflight
CStrings:
+ "(Anvil) Entitlement values for keys %{public}s are present, but the values aren't convertible to [String: Bool]!"
+ "(Anvil) Missing required keychain access groups: %{public}s"
+ "(Anvil) Required entitlement key %{public}s has value <false>"
+ "(Anvil) Unable to find %{public}s entitlement in process"
+ "(Anvil) Unable to find keychain-access-groups entitlement key in process"
+ "(Anvil) Unable to find necessary entitlement keys in process: %{public}s"
+ "ApprovalForwardingDialogHandler"
+ "ApprovalForwardingDialogHandler.chooseFromList"
+ "ApprovalForwardingDialogHandler.chooseMultipleFromList"
+ "ApprovalForwardingDialogHandler.chooseValue"
+ "ApprovalForwardingDialogHandler.showAlert"
+ "ApprovalForwardingDialogHandler.showConfirmation"
+ "AvailabilityStore"
+ "Caller responded with: %{public}s"
+ "EPS app team id (ChatGPT bundle hardcode) -> openAITeamIdentifier"
+ "EPS app team id (LS teamIdentifier) -> %{public}s"
+ "EPS app team id (bundleID fallback) -> %{public}s"
+ "EPS app team id: LSApplicationRecord init threw bundleID=%{public}s error=%{public}s"
+ "Enhanced Siri is not opted in; shouldDisableAllProviders = true"
+ "Entitlements for keys %{public}s are present, but the values aren't convertible to [String: Any]!"
+ "External sign-in restricted -- signing out failed: %@"
+ "External sign-in restricted -- signing out."
+ "GPSFeatureFlag.useV3Layout(invocationSource:) invoked from %{public}s"
+ "MDM: ExternalIntelligence not allowed; shouldDisableAllProviders = true"
+ "MDM: ExternalIntelligence sign in required, disabling all providers except for the system ChatGPT wrapper"
+ "Missing entitlements for keys %{public}s"
+ "Provider with bundle id \"%{public}s\" is remotely restricted. Hiding from both EPS platform and Settings UI."
+ "Relaying requestProtectedAppApproval(%{public}s) to caller."
+ "Sign-in disallowed but a workspace restriction requires it (misconfigured profile)."
+ "System ChatGPT wrapper has availability = .forciblyHidden, Hiding from both EPS platform and Settings UI."
+ "Workspace required but credentials have none."
+ "[AvailabilityStore.PerProviderAvailability.current(for:)] Retrieved availability status for useCaseIdentifier=%{public}s: .%{public}s, info: %{public}s"
+ "[FEATURE FLAGS] detected enhancedSiri=on"
+ "[FEATURE FLAGS] no relevant feature flags detected for #1"
+ "[FEATURE FLAGS] no relevant feature flags detected for #2"
+ "allowedExternalIntelligenceWorkspaceIDs is set but empty."
+ "allowedExternalIntelligenceWorkspaceIDs set but empty."
+ "appleIntelligenceOn"
+ "com.apple.GenerativePartnerService"
+ "com.apple.openai"
+ "com.apple.private.network.system-token-fetch"
+ "deviceManagement"
+ "enhancedSiriAssetNotReady"
+ "enhancedSiriOn"
+ "hasUserEverEnabledChatGPT: false"
+ "hasUserEverEnabledChatGPT: true - ChatGPT Extension is currently opted in"
+ "hasUserEverEnabledChatGPT: true - agentIntentHasEverBeenTurnedOffFromSettings includes ChatGPT"
+ "isExternalPartnerAllowed %{bool,public}d -- isExternalIntelligenceAllowed %{bool,public}d isMisconfigured %{bool,public}d userNeedsToSignInToWorkspace %{bool,public}d userShouldBeAnonymous %{bool,public}d"
+ "keychain-access-groups"
+ "mdmDebugAllowedExternalIntelligenceWorkspaceIDs"
+ "mdmDebugDisallowExternalIntelligence"
+ "mdmDebugDisallowExternalIntelligenceSignIn"
+ "mdmDebugRequireExternalIntelligenceWorkspaceSignIn"
+ "received AI availability update: %{public}s"
+ "received ChatGPT-specific extension availability update: %{public}s"
+ "received enhancedSiri update: %{public}s"
+ "received generativeAssistantComposition availability update: %{public}s"
+ "skipping AI availability update because cached availability is in skipCases: %{public}s; update: %{public}s"
+ "usageRestricted"
+ "useChatGPTOnlyUIForV3"
- "Campo"
- "Enhanced Siri is unavailable; returning 0 providers"
- "SimpleDialogHandler"
- "SimpleDialogHandler.chooseFromList"
- "SimpleDialogHandler.chooseMultipleFromList"
- "SimpleDialogHandler.chooseValue"
- "SimpleDialogHandler.showAlert"
- "SimpleDialogHandler.showConfirmation"
- "[AvailabilityStore.PerProviderAvailability.current(for:)] Retrieved provider status for %{public}s: .%{public}s, info: %{public}s"
- "[FEATURE FLAGS] detected Campo=on"
- "[FEATURE FLAGS] no relevant feature flags detected"
- "enhancedSiriAvailability unavailable: %s"
- "enhancedSiriAvailability: unexpected case: %s"
- "notOptedIn"
- "retrieved GM availability: %{public}s"
- "starting AvailabilityStore.GMAvailability.current()"
- "starting AvailabilityStore.PerProviderAvailability.current(for:)"
- "starting AvailabilityStore.UserFacingExternalAIRestrictedReason.current()"
- "useMontaraV2UI"
```
